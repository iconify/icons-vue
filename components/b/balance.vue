<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vss48e-1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":456};
const content = `<path class="vss48e-1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:balance" /></template>
