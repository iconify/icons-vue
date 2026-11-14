<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffwg91n5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basket-empty" /></template>
<style>
.ffwg91n5f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.329 3.165L6.536 8.75h-.891q-1.579 0-2.591 1.213t-.729 2.766l1.045 5.75q.504 2.771 3.321 2.771h10.618q2.817 0 3.321-2.771l1.045-5.75q.283-1.553-.729-2.766T18.355 8.75h-.891l-2.793-5.585q-.033-.066-.079-.125q-.045-.058-.101-.107q-.055-.048-.12-.085q-.064-.036-.134-.06q-.07-.023-.143-.032t-.147-.004t-.145.025t-.137.052t-.125.079t-.107.101t-.085.12t-.06.134t-.032.143q-.009.073-.004.147t.025.145t.052.137l2.457 4.915H8.214l2.457-4.915q.033-.066.052-.137q.02-.071.025-.145t-.004-.147t-.032-.143t-.06-.134t-.085-.12t-.107-.101t-.125-.079t-.137-.052t-.145-.025q-.074-.005-.147.004t-.143.032t-.134.06t-.12.085t-.101.107t-.079.125");
}

</style>
