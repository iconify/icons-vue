<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="udsztbpxo"/><path class="irp2ccc_j"/><path class="ya_69xzdg"/><path class="t93xzo7zo"/><path class="cxqhbvsgy"/><path class="yee_j2bln"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fluid-background" /></template>
<style>
.cxqhbvsgy {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 17.177v-5.914c0-1.114.63-3.121 2.04-4.745c2.938-1.163 7.276-2.666 7.276-1.822c0 .97-1.396 1.89-3.238 3.102c-.45.3-.93.61-1.42.95c-2.496 1.716-3.34 2.734-3.34 4.343c0 .95.272 1.638.51 2.03c-.786.573-1.455 1.256-1.828 2.056");
}

.ft5dv1b6b {
  fill: none;
}

.irp2ccc_j {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.174 8.535c0-1.289-.6-2.617-.824-3.121c.81.586 3.645 2.205 3.645 7.091c0 5.438-5.128 7.26-7.697 7.493H7.296V18.86c0-3.344 3.756-4.517 6.446-5.695c2.686-1.173 3.437-3.01 3.437-4.629z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t93xzo7zo {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.995 12.67c-.107 5.307-5.157 7.096-7.697 7.329H7.296v-.267l.039-.32c.591-3.82 5.598-4.483 9.059-4.629c2.18-.097 3.213-1.216 3.606-2.113zM4 11.264v5.913c1.028-2.19 4.256-3.504 5.976-4.052c1.726-.548 3.432-1.24 3.432-2.007c0-.765-2.35-1.056-2.35-1.822c0-.33.499-1.095 1.526-1.75c1.028-.659 2.235-1.716 2.235-2.409c0-.964-2.177-1.158-3.262-1.134C6.18 4.003 4 9.19 4 11.263");
}

.udsztbpxo {
  fill: var(--svg-color--38aade, #38aade);
  d: path("M24 0H0v24h24z");
}

.ya_69xzdg {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.297 19.9v-1.042q-.002-.306.038-.591c1.319-2.705 4.038-3.456 4.78-3.558c.775-.111 4.565-.882 6.335-1.803c.954-.494 1.294-1.537 1.362-2.424c.116.602.184 1.275.184 2.022a7.4 7.4 0 0 1-.35 2.302l-7.163 5.118l-.3.073H7.407a1 1 0 0 1-.116-.097z");
}

.yee_j2bln {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.725 4.05c.29.19.518.403.518.612c0 .508-.882 1.643-3.557 2.845C7.015 8.709 4.015 10.599 4 12.49v-1.227c0-2.074 2.186-7.26 7.557-7.26c.32-.005.736.004 1.163.048z");
}

</style>
