<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidky7lyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qidky7lyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:commandline" /></template>
