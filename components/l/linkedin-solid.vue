<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-65_mbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-65_mbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:linkedin-solid" /></template>
