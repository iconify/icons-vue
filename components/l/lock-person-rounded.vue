<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxkc1i-8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-person-rounded" /></template>
<style>
.rxkc1i-8k {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385v-8.77q0-.69.463-1.152T6.616 9H8V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.69 0 1.152.463T19 10.616v.38q0 .308-.241.507q-.242.199-.557.163q-.046-.006-.098-.01L18 11.655q-2.727-.173-4.556 1.646t-1.829 4.316q0 .461.144 1.142t.38 1.273q.142.348-.038.659q-.18.31-.528.31zm8.164-.549q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zm9.678 8.178q.438-.437.438-1.062t-.438-1.063t-1.062-.437t-1.063.437t-.437 1.063t.437 1.062t1.063.438t1.062-.438m.338 3.088q.65-.35 1.075-.975q-.576-.35-1.2-.513t-1.275-.162t-1.275.162t-1.2.513q.425.625 1.075.975t1.4.35t1.4-.35");
}

</style>
