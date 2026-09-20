<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdjwufbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdjwufbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-variant-off" /></template>
