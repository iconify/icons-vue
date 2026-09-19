<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fff0oumac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fff0oumac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:code" /></template>
