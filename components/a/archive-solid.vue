<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3343x6iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3343x6iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:archive-solid" /></template>
