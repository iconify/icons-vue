<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddfy9kbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddfy9kbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:golf-gloss" /></template>
