<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5et0bbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5et0bbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:info-circle" /></template>
