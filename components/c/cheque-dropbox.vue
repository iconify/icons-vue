<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="spvegvodp"/><path class="b7q7b6b7a"/><path class="m5e0rifmw"/><path class="f4wbfvb7k"/><path class="kvwzsc1ai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-dropbox" /></template>
<style>
.b7q7b6b7a {
  d: path("m4.5 11.5l2-2.25h11l2 2.25");
}

.f4wbfvb7k {
  d: path("M14.5 16.5h6A1.5 1.5 0 0 1 22 18v1.75a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5V18a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvwzsc1ai {
  d: path("M14.75 19.5c.75-1.5 1.5-1.5 2-.5s1.25-.75 3.25-.25");
}

.m5e0rifmw {
  fill: currentColor;
  d: path("M9.125 12.25h5.75a.625.625 0 0 1 .625.625a.625.625 0 0 1-.625.625h-5.75a.625.625 0 0 1-.625-.625a.625.625 0 0 1 .625-.625");
}

.spvegvodp {
  d: path("M10.6 21.5H5.5v-13q0-.16.008-.319t.023-.318q.016-.159.039-.317q.024-.158.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297q.061-.148.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209t.252-.196t.261-.184q.132-.088.269-.17t.278-.157t.285-.144t.292-.129t.297-.115t.303-.1t.308-.085t.311-.07t.314-.055t.317-.039t.318-.023T12 2t.319.008t.318.023t.317.039t.314.055t.311.07t.308.085t.303.1t.297.115t.292.129t.285.144q.141.075.278.157t.269.17t.261.184t.252.196q.123.102.241.209t.231.22t.22.231t.209.241q.101.124.196.252t.184.261q.088.132.17.269t.157.278t.144.285t.129.292t.115.297t.1.303t.085.308t.07.311t.055.314q.023.158.039.317q.015.159.023.318t.008.319v5.2");
}

</style>
