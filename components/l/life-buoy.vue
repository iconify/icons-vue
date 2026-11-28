<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veb_5kwla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veb_5kwla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:life-buoy" /></template>
