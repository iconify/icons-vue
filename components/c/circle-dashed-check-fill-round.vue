<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_9fq3bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_9fq3bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-check-fill-round" /></template>
