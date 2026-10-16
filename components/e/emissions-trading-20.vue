<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzhw0_b9f.css';
import '../../css/q/qd81l2bmk.css';
import '../../css/l/lq2wswb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bzhw0_b9f"/><path class="qd81l2bmk"/><path class="lq2wswb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emissions-trading-20" /></template>
