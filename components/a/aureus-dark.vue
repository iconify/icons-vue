<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydaa2vbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ydaa2vbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aureus-dark" /></template>
