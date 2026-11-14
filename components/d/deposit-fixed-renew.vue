<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vourwhbit"/><path class="qe1-ccc-d"/><path class="xcq64k0bj"/><path class="flc_k6b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-fixed-renew" /></template>
<style>
.flc_k6b4r {
  d: path("m15.5 14.5l.25 1.5l1.5.25");
}

.qe1-ccc-d {
  d: path("M17.399 11.381q-.222-.331-.482-.633q-.261-.301-.557-.569t-.622-.497t-.678-.417t-.724-.331t-.759-.24t-.782-.145Q12.399 8.5 12 8.5q-.16 0-.319.008t-.318.023t-.317.039t-.314.055q-.157.031-.311.07q-.155.039-.308.085t-.303.1t-.297.115t-.292.129t-.285.144t-.278.157t-.269.17q-.133.089-.261.184t-.252.196t-.241.209t-.231.22t-.22.231t-.209.241q-.101.124-.196.252t-.184.261q-.088.132-.17.269t-.157.278t-.144.285q-.068.144-.129.292q-.061.147-.115.297t-.1.303t-.085.308t-.07.311t-.055.314q-.023.158-.039.317q-.015.159-.023.318T5.5 15t.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297q.061.148.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209q.124.101.252.196t.261.184t.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T12 21.5q.65 0 1.286-.129m5.054-7.803q-.135-.601-.382-1.165");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vourwhbit {
  d: path("M8 9.5V7a4 4 0 0 1 8 0v2.5");
}

.xcq64k0bj {
  d: path("M12.278 12.262A3 3 0 0 0 12 12.25c-1 0-1.75.5-1.75 1.25c0 1.03 1.451 1.148 2.484 1.569m-.537 2.424Q12.1 17.5 12 17.5c-.9 0-1.55-.3-1.75-.75m1.75-5.5v1m0 5.25v1m8.121-2.621a3 3 0 1 1-4.242 0");
}

</style>
