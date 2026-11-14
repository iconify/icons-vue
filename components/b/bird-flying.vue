<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn2qa7fbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bird-flying" /></template>
<style>
.pn2qa7fbi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.897 12.864q.179.112.274.301q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18l-1.815.908Q17.436 19 11.5 19q-4.177 0-7.835-1.829q-.196-.098-.308-.285l-1.5-2.5q-.062-.104-.089-.222t-.014-.239q.015-.148.085-.28q.071-.131.186-.225q.116-.095.258-.138t.292-.028q2.746.274 5.734-.235q-2.184-2.689-3.526-7.048q-.061-.2-.011-.403q.037-.145.125-.264q.089-.12.217-.197t.276-.099q.147-.022.292.014q5.744 1.436 8.491 6.408q1.262-1.18 2.827-1.18q1.923 0 3.019 1.44z");
}

</style>
