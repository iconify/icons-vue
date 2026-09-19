<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sepwrgbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sepwrgbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:auth0" /></template>
