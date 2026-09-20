<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke1im2ojn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke1im2ojn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-plus" /></template>
