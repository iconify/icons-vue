<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu4msfb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu4msfb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-camera-movie" /></template>
