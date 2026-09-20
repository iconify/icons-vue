<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lipjsib7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-info-alert-outline-sharp" /></template>
<style>
.lipjsib7r {
  fill: currentColor;
  d: path("M3 20v-2h12v2zm9.463-8.462Q11 10.075 11 8t1.463-3.537T16 3t3.538 1.463T21 8t-1.463 3.538T16 13t-3.537-1.463M3 12v-2h6.3q.175.55.4 1.05t.55.95zm0 4v-2h9.4q.575.35 1.225.588t1.375.337V16zm12.5-5h1V7h-1zm.85-5.15q.15-.15.15-.35t-.15-.35T16 5t-.35.15t-.15.35t.15.35T16 6t.35-.15");
}

</style>
