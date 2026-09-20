<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j61x_kapz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j61x_kapz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-vision-pro" /></template>
