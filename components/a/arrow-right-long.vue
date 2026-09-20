<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncy1n-byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="ncy1n-byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-right-long" /></template>
