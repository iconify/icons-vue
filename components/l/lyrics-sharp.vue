<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc7kgssyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lyrics-sharp" /></template>
<style>
.bc7kgssyw {
  fill: currentColor;
  d: path("M6 14h4v-2H6zm13-2q-1.25 0-2.125-.875T16 9t.875-2.125T19 6q.275 0 .525.05t.475.125V1h4v2h-2v6q0 1.25-.875 2.125T19 12M6 11h7V9H6zm0-3h7V6H6zM2 22V2h15v2.425q-1.375.6-2.187 1.838T14 9t.813 2.738T17 13.575V18H6z");
}

</style>
