<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh4lapbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh4lapbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:exit" /></template>
