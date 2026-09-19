<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3w_t7krg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l3w_t7krg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:clock" /></template>
