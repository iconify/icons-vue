<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzx2o7b_o.css';
import '../../css/m/mp-vwcv-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzx2o7b_o"/><path class="mp-vwcv-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:business-processes" /></template>
