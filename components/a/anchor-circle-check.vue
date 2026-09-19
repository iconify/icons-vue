<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_td2nbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d_td2nbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:anchor-circle-check" /></template>
