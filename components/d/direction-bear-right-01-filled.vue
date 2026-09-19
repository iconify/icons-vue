<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc46xob6r.css';
import '../../css/i/ilhwmcbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lc46xob6r"/><path class="ilhwmcbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-bear-right-01-filled" /></template>
