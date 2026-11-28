<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl389c8af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl389c8af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-x" /></template>
