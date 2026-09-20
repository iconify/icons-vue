<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g20x7-8pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g20x7-8pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flag-bold" /></template>
