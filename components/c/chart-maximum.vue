<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxkr6syzc.css';
import '../../css/o/o64mo7bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pxkr6syzc"/><path class="o64mo7bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-maximum" /></template>
