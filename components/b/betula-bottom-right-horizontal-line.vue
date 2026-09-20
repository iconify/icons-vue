<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_m0xwdts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_m0xwdts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:betula-bottom-right-horizontal-line" /></template>
