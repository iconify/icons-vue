<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy5eoqe4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qy5eoqe4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-next-ltr" /></template>
