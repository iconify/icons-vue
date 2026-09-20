<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0fu9qbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0fu9qbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-circle-fill" /></template>
