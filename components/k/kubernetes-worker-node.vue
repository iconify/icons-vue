<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meg60s_rr.css';
import '../../css/l/ljo2zo11h.css';
import '../../css/x/x8r3bo3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="meg60s_rr"/><path class="ljo2zo11h"/><path class="x8r3bo3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes-worker-node" /></template>
