<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo9kk2b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zo9kk2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:decorate-filled" /></template>
