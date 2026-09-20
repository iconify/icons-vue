<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4v4ku4_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-r3-sharp" /></template>
<style>
.n4v4ku4_d {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm4.27 11.216v4.361H7.711v-4.361q-2.121-.666-3.417-1.851T3 12.133q0-2.14 2.624-3.646T12 6.98t6.376 1.506T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.902-1.891h.77v-2.012h.911l1.242 2.012h.893l-1.43-2.22q.5-.194.763-.528t.263-.845q0-.73-.469-1.127q-.468-.396-1.377-.396h-1.566zm.77-2.685v-1.71h.717q.573 0 .852.213t.278.625q0 .439-.269.655t-.848.217z");
}

</style>
