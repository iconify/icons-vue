<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxxjykb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxxjykb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coffee-togo" /></template>
