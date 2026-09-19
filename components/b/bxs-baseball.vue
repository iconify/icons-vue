<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz2zalvfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz2zalvfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-baseball" /></template>
