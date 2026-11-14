<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9fqzfb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bolt-cutter" /></template>
<style>
.v9fqzfb1n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 4.751v-.002q0-1.045 1.096-1.703q.91-.547 2.154-.547t2.154.547q1.097.658 1.096 1.703q.001 1.047-1.096 1.705q-.903.543-2.136.547l-3.895 4.921l-5.723 9.952q-.037.064-.085.12t-.107.1q-.059.045-.125.078t-.138.052t-.145.024t-.147-.004q-.073-.01-.143-.033q-.07-.024-.134-.061q-.129-.074-.22-.192t-.13-.263q-.039-.144-.02-.292t.094-.277l5.463-9.502l-1.437-1.437l-9.502 5.463q-.064.037-.134.061q-.07.023-.143.033q-.074.009-.147.004q-.074-.005-.145-.024q-.072-.019-.138-.052t-.125-.078t-.107-.1t-.085-.12t-.061-.134t-.033-.143t-.004-.147t.024-.145t.052-.138t.078-.125t.1-.107t.12-.085l9.952-5.723l4.05-3.206Q16 5.109 16 4.751m1.179 1.752l-3.553 2.812l1.059 1.059l2.907-3.672q-.214-.087-.413-.199");
}

</style>
