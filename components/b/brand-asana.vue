<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khf3n-v7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khf3n-v7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-asana" /></template>
