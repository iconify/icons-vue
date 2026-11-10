<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3co_8lgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3co_8lgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-move-left-x" /></template>
