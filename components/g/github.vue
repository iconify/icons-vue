<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7l7sbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7l7sbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:github" /></template>
