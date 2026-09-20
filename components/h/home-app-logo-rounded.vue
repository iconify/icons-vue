<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa_o1ntlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-app-logo-rounded" /></template>
<style>
.oa_o1ntlv {
  fill: currentColor;
  d: path("M6 21q-1.25 0-2.125-.875T3 18v-6q0-.6.225-1.15t.65-.975l6-6q.425-.45.988-.663T12 3t1.125.213t1 .662l.75.75L7 12.5V17h10v-4.5l-3.6-3.6l2.875-2.85l3.85 3.825q.425.425.65.975T21 12v6q0 1.25-.875 2.125T18 21z");
}

</style>
