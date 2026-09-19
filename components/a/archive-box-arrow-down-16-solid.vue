<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sleoyfbzy.css';
import '../../css/v/vrf9bubqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="sleoyfbzy"/><path clip-rule="evenodd" class="vrf9bubqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:archive-box-arrow-down-16-solid" /></template>
