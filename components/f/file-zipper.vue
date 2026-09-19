<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjw1ds2yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wjw1ds2yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-zipper" /></template>
