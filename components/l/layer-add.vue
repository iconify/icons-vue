<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_uu_bb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g_uu_bb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-add" /></template>
