<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3n4y2bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x3n4y2bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ellipsis-circle" /></template>
