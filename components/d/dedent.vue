<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t630uobct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="t630uobct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:dedent" /></template>
