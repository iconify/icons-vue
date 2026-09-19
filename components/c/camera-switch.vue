<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq5z-cv1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="eq5z-cv1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-switch" /></template>
