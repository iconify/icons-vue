<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxxl__0bs.css';
import '../../css/e/e4ngkd7is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zxxl__0bs"/><path class="e4ngkd7is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:brush" /></template>
