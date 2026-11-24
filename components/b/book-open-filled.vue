<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3-c3wbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3-c3wbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-open-filled" /></template>
