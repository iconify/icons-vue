<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="soui08bep"/><path class="msjiwlbhd"/><path class="vsx-zhb1w"/><path class="xi4o9nrmo"/><path class="s22n7ebky"/><circle class="gst-mlben"/><path class="adzrg66jr"/><path class="l3kdc7cni"/><circle class="ep9c-vjhb"/><circle class="dly4_ebcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fishing-pole" /></template>
<style>
.adzrg66jr {
  fill: var(--svg-color--269, #269);
  d: path("M8.954 22.827c-1.504 0-2.829-.538-4-1.149a1 1 0 0 1 .926-1.774c1.891.988 3.59 1.385 5.735.11a1.001 1.001 0 0 1 1.02 1.721c-1.334.792-2.558 1.092-3.681 1.092");
}

.dly4_ebcl {
  cx: 28px;
  cy: 25px;
  r: 2px;
  fill: var(--svg-color--66757f, #66757f);
}

.ep9c-vjhb {
  cx: 28px;
  cy: 25px;
  r: 4px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.gst-mlben {
  cx: 11.5px;
  cy: 15.5px;
  r: 1.5px;
}

.l3kdc7cni {
  fill: var(--svg-color--662113, #662113);
  d: path("M29.834 35.25c-.494-.247-1.042-.958-.729-1.697c1.334-3.146 4.278-16.9 1.604-24.761c-.501-1.472-2.118-3.659-4.08-4.863C20.292.042 10.823 2.171 9.5 2.833c-.495.248-2.044.744-2.292.25s.589-1.003 1.083-1.25c1.756-.877 11.264-3.878 19.667.791c1.5.833 3.59 2.376 4.703 5.303c3.257 8.567 1.047 23.416-.787 26.822c-.582 1.084-1.896.572-2.04.501");
}

.msjiwlbhd {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M2 33c0-2.236 4-6 7-6v5c-1 0-4 1-5 2s-2 0-2-1m14 0c0-2.236-4-6-7-6v5c1 0 4 1 5 2s2 0 2-1");
}

.s22n7ebky {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M9.023 11.001c-.574.63-1.856 2.332-2.481 4.415c-.875.5-.833-1.208-.708-1.75c.225-.975.506-.977.346-1.521c-.21-.551-.789-.364-1.119-.159C3.348 12.97 2 14.8 2 18c0 5.522 5 13 7 13s7-7.478 7-13c0-5.509-3.979-6.992-6.977-6.999");
}

.soui08bep {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M8 16a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0v11a1 1 0 0 1-1 1");
}

.vsx-zhb1w {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M15 14c2 0 4 1 4 2c0 3-3.167 11.542-8.167 12.542S15 14 15 14M3 20c-1 1-2 3-2 5s2.75-2.042 4-1c1.718 1.432-2-4-2-4");
}

.xi4o9nrmo {
  d: path("M5.583 12.25c1.5.5 2.583.125 3.667-.75s1.25 2.542-.25 3.667s-4.125 3.75-4.083 1.417s.666-4.334.666-4.334");
}

</style>
