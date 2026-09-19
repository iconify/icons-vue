<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwhr9xfgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="bwhr9xfgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:9-square" /></template>
