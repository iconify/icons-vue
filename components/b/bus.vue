<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf7w_yagv.css';
import '../../css/c/c834y5bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lf7w_yagv"/><path class="c834y5bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bus" /></template>
