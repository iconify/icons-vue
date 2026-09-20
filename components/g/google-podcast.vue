<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvw_2eb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvw_2eb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-podcast" /></template>
