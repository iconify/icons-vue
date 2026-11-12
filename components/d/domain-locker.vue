<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-c0av85g.css';
import '../../css/r/r1m3whbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-c0av85g"/><path class="r1m3whbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-locker" /></template>
