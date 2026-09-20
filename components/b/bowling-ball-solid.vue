<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxil07bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxil07bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bowling-ball-solid" /></template>
