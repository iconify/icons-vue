<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aysbslbjn"/><path class="lx1wo8brb"/><path class="ioli4fbza"/><path class="js-4di2ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-html" /></template>
<style>
.aysbslbjn {
  fill: var(--svg-color--e44f26, #e44f26);
  d: path("M5.902 27.201L3.655 2h24.69l-2.25 25.197L15.985 30z");
}

.ioli4fbza {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M16 13.407h-4.09l-.282-3.165H16V7.151H8.25l.074.83l.759 8.517H16zm0 8.027l-.014.004l-3.442-.929l-.22-2.465H9.221l.433 4.852l6.332 1.758l.014-.004z");
}

.js-4di2ag {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.989 13.407v3.091h3.806l-.358 4.009l-3.448.93v3.216l6.337-1.757l.046-.522l.726-8.137l.076-.83zm0-6.256v3.091h7.466l.062-.694l.141-1.567l.074-.83z");
}

.lx1wo8brb {
  fill: var(--svg-color--f1662a, #f1662a);
  d: path("m16 27.858l8.17-2.265l1.922-21.532H16z");
}

</style>
