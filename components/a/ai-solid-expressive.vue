<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fat9gabik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fat9gabik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:ai-solid-expressive" /></template>
