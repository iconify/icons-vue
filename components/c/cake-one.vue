<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/ziwosab9a.css';
import '../../css/c/cpznl-jyx.css';
import '../../css/r/rc5h_rlcn.css';
import '../../css/v/veaom2e6k.css';
import '../../css/n/n03gsccew.css';
import '../../css/k/ks2x0ybhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ziwosab9a"/><circle class="cpznl-jyx"/><path class="rc5h_rlcn"/><path class="veaom2e6k"/><path class="n03gsccew"/><path class="ks2x0ybhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cake-one" /></template>
