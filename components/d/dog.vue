<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj2r5rupy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nj2r5rupy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:dog" /></template>
