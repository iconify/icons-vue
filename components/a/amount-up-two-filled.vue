<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj166yu5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zj166yu5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-up-two-filled" /></template>
