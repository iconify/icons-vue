<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v20uw1buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v20uw1buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:file" /></template>
