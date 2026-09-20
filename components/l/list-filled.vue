<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6582di4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a6582di4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:list-filled" /></template>
