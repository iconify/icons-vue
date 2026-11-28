<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og0hiob0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og0hiob0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-ordered-solid" /></template>
