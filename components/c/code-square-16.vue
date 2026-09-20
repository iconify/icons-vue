<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecc2mpxmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ecc2mpxmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-square-16" /></template>
