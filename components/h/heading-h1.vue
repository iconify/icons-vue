<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dder4rzjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dder4rzjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:heading-h1" /></template>
