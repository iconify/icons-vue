<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhvm94b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhvm94b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:at" /></template>
