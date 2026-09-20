<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_32xbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_32xbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:door-unavailable" /></template>
