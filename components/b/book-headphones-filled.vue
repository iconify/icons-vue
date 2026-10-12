<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hford7bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hford7bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-headphones-filled" /></template>
