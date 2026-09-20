<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy6wwtboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy6wwtboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-check" /></template>
