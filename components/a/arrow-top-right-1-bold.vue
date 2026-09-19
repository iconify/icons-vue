<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdr6lg8ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdr6lg8ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-1-bold" /></template>
