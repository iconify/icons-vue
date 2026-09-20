<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t37-psbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t37-psbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:folium" /></template>
