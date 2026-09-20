<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz4ul3vvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz4ul3vvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-half-full" /></template>
