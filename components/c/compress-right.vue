<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy3tuvb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy3tuvb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:compress-right" /></template>
