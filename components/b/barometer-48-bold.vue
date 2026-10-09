<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/p/pe0xaebmw.css';
import '../../css/c/c98mb4bmh.css';
import '../../css/x/xya8plbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="pe0xaebmw"/><path class="c98mb4bmh"/><path class="xya8plbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barometer-48-bold" /></template>
