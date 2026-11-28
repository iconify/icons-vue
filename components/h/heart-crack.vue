<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf3u8xbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf3u8xbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heart-crack" /></template>
