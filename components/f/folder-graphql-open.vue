<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-4zo-uap.css';
import '../../css/m/m3lvxtb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-4zo-uap"/><path class="m3lvxtb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-graphql-open" /></template>
