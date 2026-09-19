<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4cis96ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4cis96ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:link-external" /></template>
