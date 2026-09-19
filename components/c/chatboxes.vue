<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqkz2q7yx.css';
import '../../css/w/wyaou_efh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqkz2q7yx"/><path class="wyaou_efh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatboxes" /></template>
