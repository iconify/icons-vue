<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu23513nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cu23513nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:apps-filled" /></template>
