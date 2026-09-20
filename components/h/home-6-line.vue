<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6rf2rbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6rf2rbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-6-line" /></template>
