<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6e_e6bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6e_e6bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-circle" /></template>
