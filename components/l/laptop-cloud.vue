<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uogs-ibsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uogs-ibsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:laptop-cloud" /></template>
