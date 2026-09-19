<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2zyaudgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r2zyaudgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:box-open" /></template>
