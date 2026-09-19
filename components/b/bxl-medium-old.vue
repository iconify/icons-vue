<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukonh3j0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukonh3j0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-medium-old" /></template>
