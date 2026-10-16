<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql0y1hb7o.css';
import '../../css/d/dscdkvbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ql0y1hb7o"/><path class="dscdkvbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lock-20-bold" /></template>
