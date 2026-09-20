<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3t2t0bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3t2t0bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flashpaper-dark" /></template>
