<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj4f5jigr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gj4f5jigr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-left-filled" /></template>
