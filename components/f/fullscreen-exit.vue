<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxhcf7bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxhcf7bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:fullscreen-exit" /></template>
