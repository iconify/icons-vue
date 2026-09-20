<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr00z-buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr00z-buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:leaf-fill" /></template>
