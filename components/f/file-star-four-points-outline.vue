<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um2ox6b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um2ox6b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-star-four-points-outline" /></template>
