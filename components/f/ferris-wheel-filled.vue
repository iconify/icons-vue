<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcn7k_b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcn7k_b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ferris-wheel-filled" /></template>
