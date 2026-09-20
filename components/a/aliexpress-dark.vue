<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09u8ms8j.css';
import '../../css/x/xyyx10_gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b09u8ms8j"/><path class="xyyx10_gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aliexpress-dark" /></template>
