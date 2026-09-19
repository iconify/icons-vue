<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwm3u_bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwm3u_bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bug" /></template>
