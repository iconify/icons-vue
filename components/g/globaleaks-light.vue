<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl-gwfb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zl-gwfb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:globaleaks-light" /></template>
