<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7z428y3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7z428y3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-12-fill-round" /></template>
