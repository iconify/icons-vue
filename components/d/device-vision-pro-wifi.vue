<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppkjwabgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppkjwabgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-vision-pro-wifi" /></template>
