<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e09-accts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e09-accts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:folder" /></template>
