<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdvd8x__s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdvd8x__s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:document" /></template>
