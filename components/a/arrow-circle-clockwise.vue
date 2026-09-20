<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n55x42a9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n55x42a9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-circle-clockwise" /></template>
