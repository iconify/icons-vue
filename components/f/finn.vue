<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6q3dwxxu.css';
import '../../css/x/xtwgksb_s.css';
import '../../css/r/rp7oy-b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6q3dwxxu"/><path class="xtwgksb_s"/><path class="rp7oy-b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:finn" /></template>
