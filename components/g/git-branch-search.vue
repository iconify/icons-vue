<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw17u-o_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw17u-o_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-branch-search" /></template>
