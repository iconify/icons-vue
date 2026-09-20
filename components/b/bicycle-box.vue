<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxluiabmz.css';
import '../../css/t/tsf60-bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sxluiabmz"/><path class="tsf60-bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bicycle-box" /></template>
