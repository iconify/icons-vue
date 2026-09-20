<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ho5lb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ho5lb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-amazon" /></template>
