<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0rwg3gyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0rwg3gyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:heart" /></template>
