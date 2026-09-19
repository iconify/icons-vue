<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjbh5xfec"/><path class="fc0c1qbbj"/><path class="ui64188ma"/><path class="nb1l4ccrm"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:litmatch" /></template>
<style>
.cjbh5xfec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.044 13.446l2.437 11.338a2.335 2.335 0 0 0 2.774 1.792l2.956-.635l3.296 2.13l2.13-3.297l2.956-.635a2.335 2.335 0 0 0 1.792-2.774l-2.438-11.338a2.335 2.335 0 0 0-2.773-1.792l-11.338 2.438a2.335 2.335 0 0 0-1.792 2.773");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fc0c1qbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.595 15.408a2.534 2.534 0 0 0-3.01-1.945a2.53 2.53 0 0 0-1.862 1.657a2.53 2.53 0 0 0-2.379-.745a2.534 2.534 0 0 0-1.588 3.86c1.326 2.18 5.494 3.99 5.494 3.99s3.057-3.363 3.37-5.895a2.5 2.5 0 0 0-.025-.922M7.27 37.51l5.22-2.046c.958-.381 1.29-1.23 1.396-1.701c.214-.943-.04-1.972-.652-2.628a2.14 2.14 0 0 1 .116-3.024a2.13 2.13 0 0 1 3.023.116c1.226 1.324 1.88 3.142 1.847 4.976l8.084-3.17a2.144 2.144 0 0 1 2.776 1.208a2.15 2.15 0 0 1-1.208 2.776l-1.716.675");
}

.nb1l4ccrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.407 45.203c.937-.339 2.442-1.231 2.442-1.231");
}

.ui64188ma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.647 39.999a2.14 2.14 0 0 1-1.2-4.096l3.226-1.214a2.14 2.14 0 0 1 1.507 4.006l-3.226 1.214a2 2 0 0 1-.307.09m1.251 4.093a2.14 2.14 0 0 1-.935-4.16l1.937-.612a2.13 2.13 0 0 1 2.684 1.397a2.14 2.14 0 0 1-1.397 2.684l-1.937.611a2 2 0 0 1-.352.08");
}

</style>
