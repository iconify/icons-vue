<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofo_bdcmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ofo_bdcmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-trash" /></template>
