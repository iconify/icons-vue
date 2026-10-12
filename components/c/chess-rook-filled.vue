<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oafqxwbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oafqxwbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chess-rook-filled" /></template>
