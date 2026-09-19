<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vyu93m8gd"/><path class="lxuk09iqz"/><path class="z_3754y5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-fax-machine" /></template>
<style>
.lxuk09iqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.184h37V42.1h-37zM8.717 5.9h30.566v15.284H8.717z");
}

.vyu93m8gd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.935 39.687h-.805a2.413 2.413 0 0 1-2.413-2.414V26.011a2.413 2.413 0 0 1 2.413-2.413h.805a2.413 2.413 0 0 1 2.413 2.413v11.262a2.413 2.413 0 0 1-2.413 2.414m4.825-12.871a1.609 1.609 0 1 0 3.218 0v0a1.609 1.609 0 1 0-3.217 0zm4.827 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0m4.826 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0m-9.653 4.826a1.609 1.609 0 1 0 3.218 0v0a1.609 1.609 0 1 0-3.217 0zm4.827 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0m4.826 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0m-9.653 4.827a1.609 1.609 0 1 0 3.218 0v0a1.609 1.609 0 1 0-3.217 0zm4.827 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0m4.826 0a1.609 1.609 0 1 0 3.217 0v0a1.609 1.609 0 1 0-3.217 0");
}

.z_3754y5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.37 9.118h17.695v12.067H18.37zm13.674 16.089h7.239v6.435h-7.24z");
}

</style>
