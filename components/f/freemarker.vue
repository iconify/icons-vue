<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbfh8vffk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sbfh8vffk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:freemarker" /></template>
