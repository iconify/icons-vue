<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp2--zv-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2--zv-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-check-outline" /></template>
