<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-cto4hid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cto4hid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:frying-pan-clock" /></template>
