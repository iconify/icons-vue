<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-23vibek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-23vibek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cake-3-line" /></template>
