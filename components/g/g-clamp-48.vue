<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxqv9lhyv.css';
import '../../css/c/cg6w78bdt.css';
import '../../css/z/zr4agjfqn.css';
import '../../css/s/svkr3ie9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qxqv9lhyv"/><path class="cg6w78bdt"/><path class="zr4agjfqn"/><path class="svkr3ie9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:g-clamp-48" /></template>
