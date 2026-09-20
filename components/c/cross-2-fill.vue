<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhd__6bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhd__6bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cross-2-fill" /></template>
