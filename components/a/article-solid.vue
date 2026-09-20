<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm4o4i1ir.css';
import '../../css/x/xh2cg4l2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm4o4i1ir"/><path class="xh2cg4l2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-solid" /></template>
