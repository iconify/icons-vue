<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aax8d_bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aax8d_bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:close-md" /></template>
