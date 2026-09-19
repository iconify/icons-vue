<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/our_mccad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="our_mccad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:jenkins" /></template>
