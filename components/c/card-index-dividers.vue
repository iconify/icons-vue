<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b099kxb0b"/><path class="f8gd6ccep"/><path class="ulzsr0buf"/><path class="zpr_a7pru"/><path class="njoh7gb8p"/><g class="n1mjunbsu"><circle class="ziu4urbub"/><path class="selx98jpm"/><circle class="c7v4xti-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:card-index-dividers" /></template>
<style>
.b099kxb0b {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M63.4 24.7H47.7V59l16-32.4c.5-1 .4-1.8-.3-1.9");
}

.c7v4xti-k {
  cx: 36.9px;
  cy: 54.7px;
  r: 2.5px;
}

.f8gd6ccep {
  fill: var(--svg-color--aa7d5e, #aa7d5e);
  d: path("M60.8 21.3H45.1L47.7 59l13.4-35.8c.5-1 .3-1.8-.3-1.9");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.njoh7gb8p {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M45.8 11h-22V7.6C23.8 6.2 23 5 22 5H1.9C.8 5 0 6.2 0 7.6V59h47.7V13.6c0-1.5-.9-2.6-1.9-2.6");
}

.selx98jpm {
  d: path("M23.9 52.2c-1.4 0-2.5 1.1-2.5 2.5s1.1 2.5 2.5 2.5s2.5-1.1 2.5-2.5s-1.1-2.5-2.5-2.5");
}

.ulzsr0buf {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M56.1 17.9h-8.4V59l9.4-38.8c.3-1.3-.2-2.3-1-2.3");
}

.ziu4urbub {
  cx: 10.8px;
  cy: 54.7px;
  r: 2.5px;
}

.zpr_a7pru {
  fill: var(--svg-color--f2bc97, #f2bc97);
  d: path("M52.2 13h-8.4l3.9 46l5.4-43.7c.3-1.3-.1-2.3-.9-2.3");
}

</style>
