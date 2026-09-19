<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwu36wfvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uwu36wfvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:epic-games" /></template>
