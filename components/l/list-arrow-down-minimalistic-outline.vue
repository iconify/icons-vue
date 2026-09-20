<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ujaqa9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7ujaqa9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-down-minimalistic-outline" /></template>
