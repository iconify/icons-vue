<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs7ot4bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs7ot4bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cable-car-clock" /></template>
