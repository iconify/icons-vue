<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfd85mq7p.css';
import '../../css/t/tdi20-bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfd85mq7p"/><path class="tdi20-bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flagging-taxi" /></template>
