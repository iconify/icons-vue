<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wmal69bbw"/><path class="rd-dlmbtz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kleva-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rd-dlmbtz {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.03 14.86l2.87 5.07c.053.09.181.09.23 0l5.91-10.451a.21.21 0 0 0 0-.203l-2.93-5.172a.2.2 0 0 0-.166-.101H4.131a.133.133 0 0 0-.112.202L6.392 8.28a.13.13 0 0 0 .214.021l2.612-2.676a.06.06 0 0 1 .043-.022c.037-.005.08.027.075.07c0 .01 0 .021-.011.032L4.03 14.656a.21.21 0 0 0 0 .203m10.648 3.438l5.295-8.952a.21.21 0 0 0 0-.203l-2.868-5.07a.128.128 0 0 0-.23 0l-5.913 10.45a.21.21 0 0 0 0 .203l2.933 5.172a.18.18 0 0 0 .165.101h5.812c.07 0 .123-.053.128-.122c0-.027 0-.054-.016-.08l-2.373-4.074a.13.13 0 0 0-.213-.022l-2.613 2.677a.06.06 0 0 1-.043.022a.07.07 0 0 1-.052-.019a.07.07 0 0 1-.022-.051c0-.01 0-.021.01-.032");
}

.wmal69bbw {
  fill: var(--svg-color--1a56ff, #1a56ff);
  d: path("M24 0H0v24h24z");
}

</style>
