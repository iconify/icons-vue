<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y9bzs3rih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iconzy" /></template>
<style>
.y9bzs3rih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.398 29.102L24 43.5L9.602 29.102zM13.858 6.385h9.101v9.101h-9.101zM29.397 4.5l6.435 6.436l-6.435 6.435l-6.435-6.435zM13.858 17.373h9.101v9.101h-9.101zm10.989 0h9.101v9.101h-9.101z");
}

</style>
