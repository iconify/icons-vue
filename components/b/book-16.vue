<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcy60_bxj.css';
import '../../css/d/dw8a25bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcy60_bxj"/><path clip-rule="evenodd" class="dw8a25bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:book-16" /></template>
