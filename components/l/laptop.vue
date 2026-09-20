<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_jp9ebst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_jp9ebst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:laptop" /></template>
