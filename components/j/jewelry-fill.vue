<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky-xdub6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky-xdub6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:jewelry-fill" /></template>
