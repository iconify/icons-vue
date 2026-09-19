<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3dqtccwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x3dqtccwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:code" /></template>
