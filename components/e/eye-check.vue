<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry9s8zawo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9s8zawo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:eye-check" /></template>
