<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umt5eeb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umt5eeb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:bookmark" /></template>
