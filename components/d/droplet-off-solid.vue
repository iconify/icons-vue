<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-iy5n6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-iy5n6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:droplet-off-solid" /></template>
