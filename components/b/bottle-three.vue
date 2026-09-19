<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/ripdjiu2y.css';
import '../../css/k/kxpgxsbnl.css';
import '../../css/a/an0us4bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ripdjiu2y"/><path class="kxpgxsbnl"/><rect class="an0us4bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bottle-three" /></template>
