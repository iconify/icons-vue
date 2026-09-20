<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umylk03ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="umylk03ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:broadcast" /></template>
