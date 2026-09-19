<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki14w9bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki14w9bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-camera-off" /></template>
