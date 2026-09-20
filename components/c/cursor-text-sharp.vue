<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajs828bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajs828bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-text-sharp" /></template>
