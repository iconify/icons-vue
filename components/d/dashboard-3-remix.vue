<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1tr4pbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u1tr4pbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dashboard-3-remix" /></template>
