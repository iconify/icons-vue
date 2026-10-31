<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-4o8eb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-4o8eb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-round" /></template>
