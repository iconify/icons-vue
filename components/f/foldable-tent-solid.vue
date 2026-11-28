<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag-h2id7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag-h2id7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-tent-solid" /></template>
