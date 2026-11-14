<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvb3l6bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-collectible" /></template>
<style>
.bvb3l6bak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 1.75h10.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 17.125V6.875q0-2.123 1.501-3.624T6.875 1.75M6.14 9.064Q6 9.26 6 9.5v.003q.001.211.112.391l5.25 8.5q.093.151.244.244q.127.078.274.102t.293-.01t.266-.122q.121-.087.199-.214l5.25-8.499v-.001Q18 9.713 18 9.5v-.025q-.008-.227-.14-.411l-2.5-3.5q-.052-.073-.119-.131q-.068-.059-.148-.1t-.166-.062t-.177-.021h-5.5q-.09 0-.177.021t-.166.062t-.148.1q-.067.058-.119.131z");
}

</style>
