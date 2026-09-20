<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-bh4bky.css';
import '../../css/w/w71itubsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps-bh4bky"/><path class="w71itubsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-expo-open" /></template>
