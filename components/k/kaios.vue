<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9780c6bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u9780c6bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kaios" /></template>
