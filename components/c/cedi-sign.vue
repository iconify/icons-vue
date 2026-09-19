<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1y_1lbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z1y_1lbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cedi-sign" /></template>
