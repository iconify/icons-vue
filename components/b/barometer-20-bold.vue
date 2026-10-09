<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/i/ir9wdpb0n.css';
import '../../css/x/xonacibwr.css';
import '../../css/j/ja9-u5bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="ir9wdpb0n"/><path class="xonacibwr"/><path class="ja9-u5bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barometer-20-bold" /></template>
