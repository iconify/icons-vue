<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfv4ynbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gfv4ynbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:centos-wordmark" /></template>
