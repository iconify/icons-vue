<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upkyg_b6q.css';
import '../../css/f/fz7rrmbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="upkyg_b6q"/><path class="fz7rrmbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:billing" /></template>
