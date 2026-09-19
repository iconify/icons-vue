<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvv_m2blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wvv_m2blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:close-all" /></template>
