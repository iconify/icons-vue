<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gozap8bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gozap8bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:graduation-cap" /></template>
