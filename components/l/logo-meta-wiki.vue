<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs8_8nb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vs8_8nb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-meta-wiki" /></template>
