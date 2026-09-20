<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8orw8d-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8orw8d-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-male-male-child" /></template>
