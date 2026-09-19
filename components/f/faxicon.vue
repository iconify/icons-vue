<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_wbthuz.css';
import '../../css/q/qtkf3h-or.css';
import '../../css/a/ai3a9kmls.css';
import '../../css/g/g5rjs7bks.css';
import '../../css/y/yy60akbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb_wbthuz"/><path class="qtkf3h-or"/><circle class="ai3a9kmls"/><circle class="g5rjs7bks"/><path class="yy60akbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:faxicon" /></template>
