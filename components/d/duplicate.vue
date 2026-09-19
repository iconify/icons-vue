<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx5yyubuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx5yyubuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:duplicate" /></template>
