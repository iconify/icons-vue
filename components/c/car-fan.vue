<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzn8g5yie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzn8g5yie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-fan" /></template>
