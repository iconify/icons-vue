<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn9l6bbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yn9l6bbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkwarden-dark" /></template>
