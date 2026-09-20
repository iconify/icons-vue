<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqgm24bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqgm24bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chitchatter-light" /></template>
