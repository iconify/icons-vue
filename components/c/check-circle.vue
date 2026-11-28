<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uteu266cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uteu266cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:check-circle" /></template>
