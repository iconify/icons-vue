<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lubufcyue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lubufcyue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cline" /></template>
