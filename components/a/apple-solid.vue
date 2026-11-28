<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrd05ac5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrd05ac5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:apple-solid" /></template>
