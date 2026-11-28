<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aybc_5yie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aybc_5yie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:frog" /></template>
