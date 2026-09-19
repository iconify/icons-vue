<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cno-zqbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cno-zqbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot" /></template>
