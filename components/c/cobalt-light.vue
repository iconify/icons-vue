<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkweo9bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkweo9bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cobalt-light" /></template>
