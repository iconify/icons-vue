<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os73vlb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os73vlb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:camera-off" /></template>
