<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/l2h99cbcg.css';
import '../../css/x/xmie1ejsr.css';
import '../../css/k/k-k8-gbsm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGynakgbDH"><g class="ufeehvblu"><path class="l2h99cbcg"/><path class="xmie1ejsr"/><path class="k-k8-gbsm"/></g></mask></defs><path mask="url(#SVGynakgbDH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:expand-down" /></template>
