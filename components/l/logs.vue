<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi84fdbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi84fdbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:logs" /></template>
