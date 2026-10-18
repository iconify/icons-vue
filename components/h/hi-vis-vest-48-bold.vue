<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zct-ewbsx.css';
import '../../css/i/i2xf5kbgn.css';
import '../../css/c/cx989p37d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zct-ewbsx"/><path class="i2xf5kbgn"/><path class="cx989p37d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hi-vis-vest-48-bold" /></template>
