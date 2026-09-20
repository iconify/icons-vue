<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cga2esbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cga2esbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discussion-remove-outline" /></template>
