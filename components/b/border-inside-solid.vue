<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z969ijbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z969ijbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:border-inside-solid" /></template>
