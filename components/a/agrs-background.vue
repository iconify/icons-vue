<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q5o3-ryxz"/><path class="mr9aw0jsh"/><path class="tpj697_yt"/><path class="s5dhq6pva"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:agrs-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mr9aw0jsh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.853 9.347a.87.87 0 0 0-.578.209a1.9 1.9 0 0 0-.418.55c-.12.227-.222.476-.297.756a7.5 7.5 0 0 0-.29 1.591a6 6 0 0 0-.03.578q0 .726.2 1.111a.68.68 0 0 0 .64.378a.9.9 0 0 0 .578-.2c.17-.144.312-.319.417-.516a3.3 3.3 0 0 0 .298-.724a7.7 7.7 0 0 0 .276-1.609q.026-.387.026-.666a2.7 2.7 0 0 0-.169-1.076c-.115-.258-.333-.382-.653-.382");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q5o3-ryxz {
  fill: var(--svg-color--ffc845, #ffc845);
  d: path("M24 0H0v24h24z");
}

.s5dhq6pva {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 19.556c-4.222 0-7.556-3.334-7.556-7.556S7.778 4.444 12 4.444S19.555 7.778 19.555 12S16.222 19.555 12 19.555M12 4a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

.tpj697_yt {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.231 9.44h-.275c-.151 0-.41.089-.462.43c-.205 1.4-.41 3.028-.436 3.214q-.053.307-.044.618c.013.231.07.4.12.476a.63.63 0 0 0 .4.293l-.223 1.644h-.453a3 3 0 0 1-.498-.093a1.6 1.6 0 0 1-.609-.356c-.155-.164-.31-.337-.448-.764a2 2 0 0 1-.765.858c-.252.154-.54.238-.835.244a1.88 1.88 0 0 1-1.547-.684c-.37-.458-.556-1.142-.556-2.062c0-.934.09-1.743.254-2.423c.169-.675.39-1.235.666-1.67a2.9 2.9 0 0 1 .947-.97a2.1 2.1 0 0 1 1.076-.31c.408 0 .746.093 1.013.293q.4.293.609.813s.146-.52.786-.813c.756-.347 1.45.053 1.45.053zm-3.23-4.551a7.111 7.111 0 1 0 0 14.222a7.111 7.111 0 0 0 0-14.222");
}

</style>
