<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn80i1bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn80i1bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-txt-filled" /></template>
