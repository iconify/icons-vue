<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z95sz48rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z95sz48rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-line-bold" /></template>
