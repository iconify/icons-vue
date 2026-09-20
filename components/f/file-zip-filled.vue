<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aznnbbcdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aznnbbcdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-zip-filled" /></template>
