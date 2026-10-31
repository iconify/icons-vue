<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jccexw19j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jccexw19j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-list-fill-round" /></template>
