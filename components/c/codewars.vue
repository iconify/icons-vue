<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaybfhqhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaybfhqhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codewars" /></template>
