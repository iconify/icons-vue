<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k_r1rzkra.css';
import '../../css/q/qsqtribpm.css';
import '../../css/v/v3hm9-n6v.css';
import '../../css/z/zfyrt1jby.css';
import '../../css/l/l1lryzbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k_r1rzkra"/><path clip-rule="evenodd" class="qsqtribpm"/><path class="v3hm9-n6v"/><path clip-rule="evenodd" class="zfyrt1jby"/><path class="l1lryzbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:balance-two" /></template>
