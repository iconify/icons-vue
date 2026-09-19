<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzdu60iel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nzdu60iel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:forward-step" /></template>
