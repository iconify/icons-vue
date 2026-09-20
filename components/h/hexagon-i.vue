<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3s-c3bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3s-c3bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-i" /></template>
