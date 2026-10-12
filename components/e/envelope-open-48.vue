<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6va0ihvr.css';
import '../../css/y/y_9con1lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r6va0ihvr"/><path class="y_9con1lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:envelope-open-48" /></template>
