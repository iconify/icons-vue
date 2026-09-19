<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hem6pgwtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hem6pgwtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:backward" /></template>
