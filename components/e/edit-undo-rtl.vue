<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvktn51hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qvktn51hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:edit-undo-rtl" /></template>
