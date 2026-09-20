<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4g6f4bfq.css';
import '../../css/m/ml0gmablf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4g6f4bfq"/><path class="ml0gmablf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cuda" /></template>
