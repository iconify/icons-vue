<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne_6bfb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne_6bfb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cloudinary" /></template>
