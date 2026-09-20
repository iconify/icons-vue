<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm1876bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jm1876bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-up-filled" /></template>
