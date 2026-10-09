<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0pyeiank.css';
import '../../css/r/r7c5xu-gz.css';
import '../../css/k/k_sbwgbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z0pyeiank"/><path class="r7c5xu-gz"/><path class="k_sbwgbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-branch-20" /></template>
