<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u90t3vbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u90t3vbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calculator-filled" /></template>
