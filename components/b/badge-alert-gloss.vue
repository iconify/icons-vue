<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywxtu1jxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywxtu1jxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-alert-gloss" /></template>
