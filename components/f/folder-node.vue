<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n36vjab5v.css';
import '../../css/c/cf167rjcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n36vjab5v"/><path class="cf167rjcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-node" /></template>
