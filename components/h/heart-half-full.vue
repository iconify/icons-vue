<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpe47b1df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpe47b1df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-half-full" /></template>
