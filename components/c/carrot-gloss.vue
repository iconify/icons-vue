<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wedi3hbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wedi3hbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:carrot-gloss" /></template>
