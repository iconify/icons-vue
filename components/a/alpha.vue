<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcizibcmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alpha" /></template>
<style>
.fcizibcmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.218 6.216Q18.217 9.552 17.079 12q1.138 2.448 2.139 5.784q.022.071.029.145q.007.073-.001.147q-.007.073-.029.144t-.057.136t-.082.122t-.104.103t-.122.082q-.066.034-.136.055q-.071.022-.145.029q-.073.007-.147-.001q-.073-.007-.144-.029t-.136-.057t-.122-.082t-.103-.104t-.082-.122q-.034-.066-.055-.136q-.76-2.533-1.576-4.506q-2.836 5.04-6.456 5.04q-2.578 0-4.207-2.002Q4 14.852 4 12t1.543-4.748Q7.172 5.25 9.75 5.25q3.62 0 6.456 5.04q.816-1.973 1.576-4.506q.021-.07.055-.136q.035-.065.082-.122q.046-.057.103-.104t.122-.082t.136-.057t.144-.029q.074-.008.147-.001q.074.007.145.029q.142.042.258.137q.116.094.186.225q.071.132.086.28t-.028.292M9.75 17.25q3.107 0 5.687-5.25q-2.58-5.25-5.687-5.25Q5.5 6.75 5.5 12t4.25 5.25");
}

</style>
