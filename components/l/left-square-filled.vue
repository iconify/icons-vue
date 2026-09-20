<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfhiwccbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hfhiwccbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:left-square-filled" /></template>
