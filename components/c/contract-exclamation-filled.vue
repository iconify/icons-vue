<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjbj8lbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mjbj8lbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:contract-exclamation-filled" /></template>
