<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-cto35fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-cto35fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:glass" /></template>
