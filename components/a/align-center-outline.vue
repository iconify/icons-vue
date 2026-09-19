<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0xbtfb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0xbtfb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:align-center-outline" /></template>
