<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zjlxi5bpv.css';
import '../../css/r/rbmb9m21o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjlxi5bpv"/><path clip-rule="evenodd" class="rbmb9m21o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:checkmark-circle-checked" /></template>
