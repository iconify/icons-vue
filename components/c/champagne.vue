<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmi3hzihb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmi3hzihb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:champagne" /></template>
