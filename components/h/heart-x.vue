<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzor5qb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzor5qb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-x" /></template>
