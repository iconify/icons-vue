<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2g4xxswo.css';
import '../../css/d/doqrq2blo.css';
import '../../css/u/uf8ttfzhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2g4xxswo"/><path class="doqrq2blo"/><path class="uf8ttfzhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-build" /></template>
