<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r0lak5b4d"/><path class="mt78l7b8u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:loka-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mt78l7b8u {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.001 12.94l7.058 7.058s-1.976-3.378-2.917-4.333c-.941-.941-4.14-2.725-4.14-2.725m5.646-2.351l-5.505 1.43c-.076.02-.118.075-.141.146a.19.19 0 0 0 .084.184l3.717 2.38c.156.109.334.118.518.057a.52.52 0 0 0 .334-.395zm3.764 3.764l-1.388 5.505a.18.18 0 0 1-.33.051l-2.418-3.684a.53.53 0 0 1-.056-.517a.56.56 0 0 1 .386-.344zM9.883 10.12l1.646-5.957a.14.14 0 0 0-.056-.142q-.086-.047-.15.024l-7.284 7.274c-.047.042-.047.094-.024.15c.033.052.085.076.142.052zm3.999 4.233L12.47 19.84a.14.14 0 0 0 .057.142q.085.048.15-.024l7.284-7.274c.047-.042.047-.094.023-.15c-.033-.052-.084-.076-.14-.052zm0-.471l5.505-1.845a.19.19 0 0 0 .141-.14a.15.15 0 0 0-.084-.16l-3.774-2.01a.64.64 0 0 0-.517-.047a.49.49 0 0 0-.34.358zm-3.529-3.764l1.506-5.966c.019-.08.07-.141.141-.15s.141.023.17.094l2.093 4.117a.66.66 0 0 1 .047.564a.56.56 0 0 1-.362.381zm-.235.472l3.797-.922s.555-.155.414.452a908 908 0 0 1-.918 3.764l-3.764.931s-.55.123-.46-.517c.093-.626.931-3.708.931-3.708m2.352-6.588L20 11.53s-3.736-1.694-4.673-2.705C14.4 7.808 12.47 4.002 12.47 4.002");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r0lak5b4d {
  fill: var(--svg-color--126bf9, #126bf9);
  d: path("M24 0H0v24h24z");
}

</style>
