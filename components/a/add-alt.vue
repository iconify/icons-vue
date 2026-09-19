<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoi3q_b_l.css';
import '../../css/w/w9c6qv_hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qoi3q_b_l"/><path class="w9c6qv_hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-alt" /></template>
