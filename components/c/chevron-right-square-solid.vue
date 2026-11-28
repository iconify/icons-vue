<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbwv8vb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbwv8vb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-right-square-solid" /></template>
