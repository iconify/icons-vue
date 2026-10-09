<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-rr4hcr.css';
import '../../css/t/tjeffabft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iq-rr4hcr"/><path class="tjeffabft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-left-20" /></template>
