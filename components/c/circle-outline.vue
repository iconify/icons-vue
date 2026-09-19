<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu_o6abjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lu_o6abjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circle-outline" /></template>
