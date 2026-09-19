<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/c/c9lv-cbco.css';
import '../../css/k/kn7lbygey.css';
import '../../css/o/o712a_czv.css';
import '../../css/d/d0nxhzblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="c9lv-cbco"/><path class="kn7lbygey"/><path class="o712a_czv"/><circle class="d0nxhzblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hair-dryer-one" /></template>
