<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrh60-b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="jrh60-b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-right-long-expressive" /></template>
