<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no9jctb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no9jctb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-download" /></template>
