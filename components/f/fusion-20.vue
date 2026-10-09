<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-zna8aim.css';
import '../../css/q/qjyultakh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-zna8aim"/><path class="qjyultakh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fusion-20" /></template>
