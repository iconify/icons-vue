<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf7wu2l-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wf7wu2l-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:layout-ltr" /></template>
