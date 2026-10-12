<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtwowz7gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wtwowz7gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-down-20" /></template>
