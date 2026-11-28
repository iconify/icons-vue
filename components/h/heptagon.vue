<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do9zq7gwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do9zq7gwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heptagon" /></template>
