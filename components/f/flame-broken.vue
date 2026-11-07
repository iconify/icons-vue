<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i19p1mgnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i19p1mgnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flame-broken" /></template>
