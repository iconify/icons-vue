<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98xrwbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h98xrwbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ambys-light" /></template>
