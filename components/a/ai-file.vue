<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf794qb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf794qb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-file" /></template>
