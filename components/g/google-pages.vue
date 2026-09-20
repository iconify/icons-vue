<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv2brabrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv2brabrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-pages" /></template>
