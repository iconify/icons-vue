<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qqshb_imp"/><path clip-rule="evenodd" class="ns_77f6ss"/><path clip-rule="evenodd" class="gymh0eb2o"/><path class="ahw-ohbqu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:koin-background" /></template>
<style>
.ahw-ohbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.556 12.177L5.121 8.555l.386-.658l6.494 3.658L18.338 7.9l.387.65l-6.28 3.626v7.258h-.889z");
}

.ft5dv1b6b {
  fill: none;
}

.gymh0eb2o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 9.333l-2.222 1.31v2.712L12 14.666l2.222-1.311v-2.711zm3.11.889L12 8.444l-3.111 1.778v3.555l3.11 1.778l3.112-1.778z");
}

.ns_77f6ss {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4.871L5.778 8.436v7.129L12 19.129l6.222-3.565V8.437zM19.11 8L12 4L4.889 8v8l7.11 4l7.112-4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qqshb_imp {
  fill: var(--svg-color--6f00f6, #6f00f6);
  d: path("M24 0H0v24h24z");
}

</style>
