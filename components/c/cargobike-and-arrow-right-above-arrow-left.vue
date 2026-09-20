<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1-iebxfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t1-iebxfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-arrow-right-above-arrow-left" /></template>
