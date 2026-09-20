<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrju-_2fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yrju-_2fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crown-sharp-fill" /></template>
