<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e55-w7bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e55-w7bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:code-x" /></template>
