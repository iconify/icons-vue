<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fki9ziffh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fki9ziffh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluesky-solid" /></template>
