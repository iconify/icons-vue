<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk7zhccdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk7zhccdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-music-outline" /></template>
