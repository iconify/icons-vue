<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qf6_lqbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deezer-alt" /></template>
<style>
.qf6_lqbei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 29.88h9.75v5.88H4.5zm9.75 0H24v5.88h-9.75zm9.75 0h9.75v5.88H24zm9.75 0h9.75v5.88h-9.75zM14.25 24H24v5.88h-9.75zM24 24h9.75v5.88H24zm9.75 0h9.75v5.88h-9.75zm-19.5-5.88H24V24h-9.75zm19.5 0h9.75V24h-9.75zm0-5.89h9.75v5.88h-9.75z");
}

</style>
