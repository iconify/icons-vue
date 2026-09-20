<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2geoobln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2geoobln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:glass-juice-1" /></template>
