<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0oikac5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0oikac5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-vertical-s-fill" /></template>
