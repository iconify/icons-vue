<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k63c5w7qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k63c5w7qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-down-line" /></template>
