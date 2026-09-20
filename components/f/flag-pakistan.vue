<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7wzorbif.css';
import '../../css/t/tsvbfvbzz.css';
import '../../css/u/uzff1nbwh.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o7wzorbif"/><path class="tsvbfvbzz"/><path class="uzff1nbwh"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-pakistan" /></template>
