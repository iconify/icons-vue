<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5zx90bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5zx90bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-left-solid" /></template>
