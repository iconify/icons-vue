<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gebj2bpbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gebj2bpbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-arrow-right-outline" /></template>
