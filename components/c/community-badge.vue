<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbpnnobtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:community-badge" /></template>
<style>
.sbpnnobtg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 9q0-2.796 1.977-4.773T12 2.25t4.773 1.977T18.75 9t-1.977 4.773q-.221.221-.452.417l1.657 6.628q.031.127.018.257t-.069.247q-.032.067-.076.126q-.044.06-.099.109t-.118.087q-.064.038-.133.063q-.07.025-.143.035t-.147.007t-.145-.022t-.138-.05L12 19.331l-4.928 2.346q-.117.056-.247.069t-.257-.018q-.072-.018-.138-.05q-.067-.031-.126-.075q-.06-.044-.109-.099q-.05-.055-.088-.118t-.063-.133t-.036-.143t-.007-.146q.003-.074.021-.146l1.657-6.628q-.231-.196-.452-.417Q5.25 11.796 5.25 9M8.5 9q0-3.5 3.5-3.5T15.5 9T12 12.5T8.5 9m.505 6.072l-1.142 4.567l3.815-1.816q.075-.036.157-.055q.081-.018.165-.018t.165.018q.082.019.157.055l3.815 1.816l-1.142-4.567q-1.357.678-2.995.678t-2.995-.678");
}

</style>
