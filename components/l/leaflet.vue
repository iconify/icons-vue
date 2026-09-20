<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcuv_6byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcuv_6byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:leaflet" /></template>
