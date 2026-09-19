<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vly4rr3ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vly4rr3ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-aax" /></template>
