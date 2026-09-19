<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctktdvbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ctktdvbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-stroke-16" /></template>
