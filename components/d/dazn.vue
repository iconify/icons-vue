<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taj1kvzso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taj1kvzso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dazn" /></template>
