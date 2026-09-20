<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp53ru0ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp53ru0ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-from-arc" /></template>
