<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey9xu1u9w.css';
import '../../css/z/zn204jbmn.css';
import '../../css/f/f01zc3pzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ey9xu1u9w"/><path class="zn204jbmn"/><path clip-rule="evenodd" class="f01zc3pzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-graph-bold" /></template>
