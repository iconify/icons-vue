<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx3q0nbmz.css';
import '../../css/e/e4e471wzp.css';
import '../../css/e/eziplt3ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="kx3q0nbmz"/><path class="e4e471wzp"/><path class="eziplt3ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hole-filling-cursor" /></template>
