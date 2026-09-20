<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lquupobmq.css';
import '../../css/p/pln5qlbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lquupobmq"/><path class="pln5qlbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ellipses-horizontal-circle" /></template>
