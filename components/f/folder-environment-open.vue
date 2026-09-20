<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-fmsbcaz.css';
import '../../css/t/tpfmbf6bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-fmsbcaz"/><path class="tpfmbf6bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-environment-open" /></template>
