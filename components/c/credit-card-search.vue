<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud-3rhbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud-3rhbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:credit-card-search" /></template>
