<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9aelcbhd.css';
import '../../css/m/mxjolcg6d.css';
import '../../css/s/sm2bgibef.css';
import '../../css/e/eutl42kwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9aelcbhd"/><path class="mxjolcg6d"/><circle class="sm2bgibef"/><path class="eutl42kwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:door" /></template>
