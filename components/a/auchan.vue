<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ae2hobhik"/><circle class="yutizl0lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auchan" /></template>
<style>
.ae2hobhik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.1 39.87l-3.315-9.792c4.655.046 9.526-2.392 11.347-6.937c1.352-3.373 2.732-6.79 3.122-10.419c.762-.42 3.246-1.86 3.246-1.86l-3.671-.215s-1.779-2.101-3.034-2.35c-2.7-.537-5.856.222-7.969 2.18c-4.054 3.194-12.255 10.276-12.255 10.276H4.5c.386 2.826 3.237 4.62 5.933 4.765c-.8 1.05-2.42 2.815-2.42 2.815s9.597.29 13.405-.279c4.298-.87 8.098-3.712 10.316-7.43c-1.304 3.667-4.73 6.962-8.386 8.36l3.736 10.866zm3.237-.019l-2.68-8.182");
}

.yutizl0lm {
  cx: 35.63px;
  cy: 11.883px;
  r: 0.75px;
  fill: currentColor;
}

</style>
