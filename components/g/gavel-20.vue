<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltt_btmrh.css';
import '../../css/z/zjsm6-byf.css';
import '../../css/b/bxl44g1ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ltt_btmrh"/><path class="zjsm6-byf"/><path class="bxl44g1ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gavel-20" /></template>
