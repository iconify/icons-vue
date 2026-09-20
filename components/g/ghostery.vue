<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f574bg4zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f574bg4zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ghostery" /></template>
