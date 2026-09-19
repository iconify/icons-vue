<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ardd9_bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ardd9_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrange-by-numbers-1-9" /></template>
