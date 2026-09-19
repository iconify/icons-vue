<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_b0f49ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_b0f49ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:heptagon-fill" /></template>
