<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxppqcwvg.css';
import '../../css/q/qttbk144e.css';
import '../../css/h/h_99_tbbf.css';
import '../../css/s/sp07t1b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxppqcwvg"/><path class="qttbk144e"/><path class="h_99_tbbf"/><path class="sp07t1b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-rose" /></template>
