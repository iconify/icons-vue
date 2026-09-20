<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l64_-xbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l64_-xbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coat-hanger" /></template>
