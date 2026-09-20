<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa8_evbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa8_evbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:chevron-left" /></template>
