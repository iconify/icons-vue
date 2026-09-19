<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/ajyf3nzah.css';
import '../../css/s/sqkeg0bva.css';
import '../../css/w/wk-pusb9i.css';
import '../../css/a/aiy3-ubty.css';
import '../../css/k/k39therxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ajyf3nzah"/><path class="sqkeg0bva"/><circle class="wk-pusb9i"/><circle class="aiy3-ubty"/><circle class="k39therxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hold-seeds" /></template>
