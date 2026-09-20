<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkimz4wbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkimz4wbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:anticlockwise-2-fill" /></template>
