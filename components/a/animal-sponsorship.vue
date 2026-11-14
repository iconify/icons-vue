<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="entlb0suj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-sponsorship" /></template>
<style>
.entlb0suj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.811 14.503Q14 14.012 14 13.5q0-.172-.022-.343t-.064-.34q-.044-.168-.108-.333t-.149-.323q-.084-.159-.188-.311q-.105-.152-.227-.294q-.123-.143-.263-.276t-.297-.255t-.327-.231T12 10.59t-.379-.177t-.399-.147t-.416-.115t-.428-.084q-.217-.033-.437-.05T9.5 10t-.441.017t-.437.05t-.428.084t-.416.115q-.204.066-.399.147T7 10.59t-.355.204q-.171.11-.327.231t-.297.255q-.14.133-.263.276q-.122.142-.227.294q-.104.152-.188.311q-.085.158-.149.323t-.108.333q-.043.169-.064.34T5 13.5q0 .172.022.343t.064.34q.044.168.108.333t.149.323q.084.159.188.311q.105.152.227.294q.123.143.263.276t.297.255q.156.121.327.231q.171.109.355.204q.184.096.379.177t.399.147t.416.115q.211.05.428.084q.217.033.437.05T9.5 17q.431 0 .853-.063q.423-.064.823-.189q.399-.124.761-.306q.362-.181.673-.413M2.75 7.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.25 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18 21.5l-2.75-3.25a1.6 1.6 0 0 1 2.75-1.5a1.6 1.6 0 0 1 2.75 1.5Z");
}

</style>
