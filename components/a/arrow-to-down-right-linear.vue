<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdtrcfbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdtrcfbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-right-linear" /></template>
