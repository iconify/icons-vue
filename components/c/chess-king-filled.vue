<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y66bur87w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y66bur87w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chess-king-filled" /></template>
