<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw8l5ib2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw8l5ib2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:drone-24px" /></template>
