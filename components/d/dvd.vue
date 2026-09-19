<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2y7jzbmz.css';
import '../../css/w/wu4cddcrq.css';
import '../../css/e/e8sy34j2t.css';
import '../../css/u/ulh87kb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2y7jzbmz"/><path class="wu4cddcrq"/><path class="e8sy34j2t"/><path class="ulh87kb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dvd" /></template>
