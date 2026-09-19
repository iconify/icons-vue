<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_5_a3imy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_5_a3imy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-merge-queue" /></template>
