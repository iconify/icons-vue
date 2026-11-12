<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvrfp6bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvrfp6bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-flame" /></template>
