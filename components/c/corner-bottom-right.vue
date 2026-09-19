<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0y7sbc5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0y7sbc5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:corner-bottom-right" /></template>
