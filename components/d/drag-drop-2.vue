<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9he1imzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9he1imzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:drag-drop-2" /></template>
