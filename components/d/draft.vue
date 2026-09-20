<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvp2efblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvp2efblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:draft" /></template>
