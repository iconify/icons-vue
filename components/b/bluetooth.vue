<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u__lelkgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u__lelkgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bluetooth" /></template>
