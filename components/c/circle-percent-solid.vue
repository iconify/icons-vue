<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn7a6mbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn7a6mbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-percent-solid" /></template>
