<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btho6youx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-rating" /></template>
<style>
.btho6youx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25H5q-1.346 0-2.298.952T1.75 5.5V14q0 3.25 3.25 3.25h.25v3.25q0 .149.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l3.781-3.78H19q3.25 0 3.25-3.25V5.5q0-1.346-.952-2.298T19 2.25m-5.804 4.471l.159.396q.171.427.629.469l.512.047q.865.079 1.134.906t-.386 1.401l-.36.314q-.32.28-.244.699l.106.583q.156.862-.576 1.343t-1.461-.005l-.293-.195q-.416-.277-.832 0l-.293.195q-.729.486-1.461.005t-.576-1.343l.106-.583q.076-.419-.244-.699l-.36-.315q-.655-.572-.386-1.4q.269-.827 1.135-.906l.51-.047q.459-.042.63-.468l.159-.397q.325-.809 1.196-.809t1.196.808z");
}

</style>
