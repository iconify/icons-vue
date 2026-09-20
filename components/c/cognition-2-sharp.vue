<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejz74wbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cognition-2-sharp" /></template>
<style>
.ejz74wbrg {
  fill: currentColor;
  d: path("M7 21v-3.762q-1.425-1.3-2.212-2.922T4 10.986q0-3.327 2.333-5.657T12 3q2.702 0 4.884 1.645t2.83 4.25L20.987 14H18v5h-4v2zm2.477-7.02q.893 0 1.51-.609l3.381-3.381q.613-.613.613-1.506t-.61-1.509q-.616-.61-1.509-.61t-1.502.61q-.771-.286-1.537-.13t-1.294.684t-.685 1.294t.131 1.537q-.61.616-.61 1.509t.61 1.502t1.502.61");
}

</style>
