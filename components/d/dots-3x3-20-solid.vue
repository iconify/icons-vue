<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu-u_113z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eu-u_113z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3-20-solid" /></template>
