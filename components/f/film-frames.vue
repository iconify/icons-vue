<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f196jybrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f196jybrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:film-frames" /></template>
