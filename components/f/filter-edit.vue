<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9sgtebnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:filter-edit" /></template>
<style>
.g9sgtebnw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.399 3.25H7.101q-1.564 0-2.248 1.407t.282 2.637l2.901 3.693q.214.272.214.618v5.379q0 1.105.956 1.66t1.916.007l.868-.496q1.26-.72 1.26-2.171v-4.379q0-.346.214-.618l2.901-3.693q.966-1.23.282-2.637T14.399 3.25m.119 16.463v-.001l.155-.698q.142-.641.606-1.104l3.316-3.315q.582-.583 1.405-.583t1.406.583t.582 1.405q0 .823-.583 1.406l-3.316 3.315q-.462.464-1.102.606l-.7.155q-.794.177-1.37-.399t-.399-1.37");
}

</style>
