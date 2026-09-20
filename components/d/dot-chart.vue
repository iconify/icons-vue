<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an8hljbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="an8hljbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:dot-chart" /></template>
