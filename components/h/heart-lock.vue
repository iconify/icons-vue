<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-ssccia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-lock" /></template>
<style>
.d9-ssccia {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 9.499q1.109.362 1.999 1.252q1.501 1.501 1.501 3.624v2.75q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 17.125v-2.75q0-2.123 1.501-3.624q.89-.89 1.999-1.252V7q0-2.175 1.538-3.712Q9.825 1.75 12 1.75t3.712 1.538Q17.25 4.825 17.25 7zm-9-.248l.125-.001h7.25l.125.001V7q0-3.75-3.75-3.75T8.25 7zm3.22 10.029q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.75-2.75q.115-.114.172-.266q.656-1.747-.725-3.002q-1.243-1.13-2.727-.578q-1.484-.552-2.727.578q-1.381 1.255-.725 3.002q.057.152.172.266z");
}

</style>
