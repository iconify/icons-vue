<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8jg3rppc.css';
import '../../css/x/xh_480b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8jg3rppc"/><path class="xh_480b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kettle-48-bold" /></template>
