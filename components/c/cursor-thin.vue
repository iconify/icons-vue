<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxg9tc2er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxg9tc2er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cursor-thin" /></template>
