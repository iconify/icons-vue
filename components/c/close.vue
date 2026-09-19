<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opd2-3bgk.css';
import '../../css/u/uuunrrbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="opd2-3bgk"/><path class="uuunrrbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:close" /></template>
