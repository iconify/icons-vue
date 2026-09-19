<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab118kbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ab118kbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-arrow-right" /></template>
