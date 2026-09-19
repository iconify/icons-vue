<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8rpofbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8rpofbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:direction-up-right" /></template>
