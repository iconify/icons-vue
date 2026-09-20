<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5jb4sbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5jb4sbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-t-circle-outline" /></template>
