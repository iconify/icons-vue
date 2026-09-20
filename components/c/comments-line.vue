<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1as3j5uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1as3j5uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comments-line" /></template>
