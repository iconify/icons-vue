<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so2i40b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="so2i40b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ferris-wheel-bold" /></template>
