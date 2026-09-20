<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecktfepqc.css';
import '../../css/q/qd7nioben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ecktfepqc"/><path class="qd7nioben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:drop" /></template>
