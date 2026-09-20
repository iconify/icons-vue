<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-aezo88y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-aezo88y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:instagram" /></template>
