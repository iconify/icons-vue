<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx0k0_bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx0k0_bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:first-aid-check" /></template>
