<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wwph4-thy.css';
import '../../css/q/qn_rm7nsa.css';
import '../../css/c/colb0kncr.css';
import '../../css/n/nj53t_b7z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrzf06dUr"><g class="ufeehvblu"><path class="wwph4-thy"/><path clip-rule="evenodd" class="qn_rm7nsa"/><path class="colb0kncr"/><path class="nj53t_b7z"/></g></mask></defs><path mask="url(#SVGrzf06dUr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:calendar-thirty-two" /></template>
