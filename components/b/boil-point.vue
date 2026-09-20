<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp3z8jnam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp3z8jnam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boil-point" /></template>
