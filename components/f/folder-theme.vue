<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5fxn4-5j.css';
import '../../css/t/t38mnib2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="t38mnib2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-theme" /></template>
