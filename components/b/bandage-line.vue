<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emcn7xcoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emcn7xcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bandage-line" /></template>
