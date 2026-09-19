<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2i3shp5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="w2i3shp5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:google-drive" /></template>
