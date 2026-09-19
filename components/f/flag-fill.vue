<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h10ri2bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h10ri2bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:flag-fill" /></template>
