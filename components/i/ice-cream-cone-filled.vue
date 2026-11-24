<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpyhw8k_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpyhw8k_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ice-cream-cone-filled" /></template>
