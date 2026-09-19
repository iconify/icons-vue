<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqmy5ybif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqmy5ybif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:berlin" /></template>
