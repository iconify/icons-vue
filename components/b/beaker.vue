<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa3dtqdna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa3dtqdna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:beaker" /></template>
