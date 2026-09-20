<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d29euzbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d29euzbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flame-bold" /></template>
