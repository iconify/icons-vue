<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/s_fep1eov.css';
import '../../css/f/fdc_qf35n.css';
import '../../css/a/arhzl8byt.css';
import '../../css/l/lps7apgwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="s_fep1eov"/><path class="fdc_qf35n"/><path class="arhzl8byt"/><circle class="lps7apgwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hair-dryer-one" /></template>
