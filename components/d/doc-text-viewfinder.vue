<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayvakk8ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ayvakk8ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-text-viewfinder" /></template>
