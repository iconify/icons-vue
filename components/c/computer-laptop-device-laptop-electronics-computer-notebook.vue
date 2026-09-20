<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p01i7hbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p01i7hbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-laptop-device-laptop-electronics-computer-notebook" /></template>
