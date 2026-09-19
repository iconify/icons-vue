<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps6n6j5jn.css';
import '../../css/t/ttigw5b6h.css';
import '../../css/e/ej8id9bze.css';
import '../../css/e/eyppoibfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ps6n6j5jn"/><path class="ttigw5b6h"/><path class="ej8id9bze"/><path class="eyppoibfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bunny" /></template>
