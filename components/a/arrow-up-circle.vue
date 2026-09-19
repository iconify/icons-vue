<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en29hfbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en29hfbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-circle" /></template>
