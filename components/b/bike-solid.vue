<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7zp2bcpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7zp2bcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bike-solid" /></template>
