<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxi6bp23l.css';
import '../../css/f/fmxdhkgfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxi6bp23l"/><path class="fmxdhkgfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-circle-up" /></template>
