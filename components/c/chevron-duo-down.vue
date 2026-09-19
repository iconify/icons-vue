<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wax1c9b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wax1c9b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-duo-down" /></template>
