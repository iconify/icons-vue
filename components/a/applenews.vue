<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu3lde57s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3lde57s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:applenews" /></template>
