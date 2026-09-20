<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhj3enbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lhj3enbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:button" /></template>
