<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsr46tb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsr46tb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eyedropper-off" /></template>
