<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryjictvra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryjictvra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-distance" /></template>
