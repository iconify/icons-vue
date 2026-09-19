<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlaltv3jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlaltv3jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diamond-plus" /></template>
