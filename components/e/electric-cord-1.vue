<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg9vbachl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rg9vbachl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:electric-cord-1" /></template>
