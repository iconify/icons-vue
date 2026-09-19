<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne96gebqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ne96gebqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-2-fill" /></template>
