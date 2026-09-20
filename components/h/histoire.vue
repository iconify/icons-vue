<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuq04pbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kuq04pbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:histoire" /></template>
