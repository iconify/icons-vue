<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py0818beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py0818beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clockwise-fill" /></template>
