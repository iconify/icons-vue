<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr0d2pbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gr0d2pbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:info-board" /></template>
