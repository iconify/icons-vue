<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-6-mabzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-6-mabzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-plus-filled" /></template>
