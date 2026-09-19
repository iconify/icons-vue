<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-03gibjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1408};
const content = `<path class="c-03gibjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:info" /></template>
