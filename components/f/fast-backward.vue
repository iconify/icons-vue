<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmhk9_7ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhk9_7ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:fast-backward" /></template>
