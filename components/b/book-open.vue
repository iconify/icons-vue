<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byndn5bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="byndn5bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book-open" /></template>
