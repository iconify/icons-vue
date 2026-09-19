<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyb0b6a3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyb0b6a3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-down" /></template>
