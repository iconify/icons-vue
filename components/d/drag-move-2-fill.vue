<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3-s51bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3-s51bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drag-move-2-fill" /></template>
