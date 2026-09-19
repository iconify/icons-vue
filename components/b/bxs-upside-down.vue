<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwlm1_b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwlm1_b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-upside-down" /></template>
