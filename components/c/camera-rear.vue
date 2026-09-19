<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkvh0lmav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":512};
const content = `<path class="hkvh0lmav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-rear" /></template>
