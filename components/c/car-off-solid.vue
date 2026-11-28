<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxf9zc3us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxf9zc3us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:car-off-solid" /></template>
