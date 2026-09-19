<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6r_bpbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1344};
const content = `<path class="a6r_bpbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:keyboard" /></template>
