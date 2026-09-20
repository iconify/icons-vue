<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od2f99bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od2f99bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-center-line" /></template>
