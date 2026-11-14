<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl0xxioiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:iced-tea" /></template>
<style>
.tl0xxioiw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.422 4.75h9.62l.74-2.466q.021-.07.055-.136q.035-.065.082-.122q.046-.057.103-.104t.122-.082t.136-.057t.144-.029q.074-.008.147-.001q.074.007.145.029q.142.042.258.137q.116.094.186.225q.071.132.086.28t-.028.292l-.61 2.034q1.085.011 1.819.816q.744.817.641 1.917l-1.172 12.5q-.212 2.268-2.49 2.267H7.594q-2.278.001-2.49-2.267l-1.172-12.5q-.103-1.1.641-1.917q.744-.816 1.849-.816m3.328 3.5h-.5Q7 8.25 7 10.5v.5q0 .932.659 1.591t1.591.659h.5q.932 0 1.591-.659T12 11v-.5q0-2.25-2.25-2.25m2.5 6.25Q10 14.5 10 16.75v.5q0 2.25 2.25 2.25h.5q2.25 0 2.25-2.25v-.5q0-2.25-2.25-2.25z");
}

</style>
