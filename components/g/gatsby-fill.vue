<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0p60rdek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0p60rdek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gatsby-fill" /></template>
