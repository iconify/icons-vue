<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u19-v4beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u19-v4beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:decimals-arrow-left" /></template>
