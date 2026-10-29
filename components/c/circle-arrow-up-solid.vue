<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9r2uab5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9r2uab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-up-solid" /></template>
