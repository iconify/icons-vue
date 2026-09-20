<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im8el_gaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im8el_gaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chrome-line" /></template>
