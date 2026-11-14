<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xlf05eb_c"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:labor-hours" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlf05eb_c {
  d: path("M4 12.5v-3q0-.16.008-.319t.023-.318q.016-.159.039-.317q.024-.158.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297q.061-.148.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209q.124-.101.252-.196t.261-.184q.132-.088.269-.17t.278-.157t.285-.144t.292-.129t.297-.115t.303-.1t.308-.085t.311-.07t.314-.055q.158-.023.317-.039q.159-.015.318-.023T10.5 3t.319.008t.318.023t.317.039t.314.055t.311.07t.308.085t.303.1t.297.115t.292.129t.285.144q.141.075.278.157t.269.17q.133.089.261.184t.252.196q.123.102.241.209t.231.22t.22.231t.209.241t.196.252t.184.261q.088.132.17.269t.157.278q.076.141.144.285t.129.292t.115.297q.054.15.1.303t.085.308t.07.311t.055.314t.039.317t.023.318T17 9.5V12m-4.5 3.5h-10v-3h13m-5-9.5v4m4.25 11a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

</style>
