<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5wb_anb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un5wb_anb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:home-fill" /></template>
