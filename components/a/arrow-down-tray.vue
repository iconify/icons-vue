<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhoebv3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhoebv3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-tray" /></template>
