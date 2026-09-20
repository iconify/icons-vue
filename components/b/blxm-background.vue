<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i14sf2byk"/><path clip-rule="evenodd" class="h04d7xbje"/><path clip-rule="evenodd" class="y9cegcu0k"/><path class="gl_niobut"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blxm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gl_niobut {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.235 10.588v1.882l3.764-3.53c.156-.155.377-.564 0-.94c-.376-.377-.786-.156-.94 0zm-.47 2.56v-1.883l-3.766 3.53c-.155.16-.376.565 0 .941c.377.377.786.16.942 0z");
}

.h04d7xbje {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 18.587A6.588 6.588 0 1 0 12 5.41a6.588 6.588 0 0 0 0 13.177m-.236-6.145v-1.883L8.941 7.971c-.156-.155-.565-.377-.942 0c-.376.376-.155.786 0 .941zm.47.734v-1.883L16 14.823c.156.155.377.564 0 .94c-.376.377-.786.156-.94 0zm-2.508-6.23a.47.47 0 0 0-.63.696l2.588 2.353a.47.47 0 0 0 .63 0l2.589-2.353a.47.47 0 0 0-.285-.838a.47.47 0 0 0-.346.141L12 9.011zm7.19 2.281a.47.47 0 0 0-.658.269l-.597 1.797h-1.544a.472.472 0 0 0-.353.782l1.647 1.882a.47.47 0 0 0 .706-.621l-.965-1.101H16a.47.47 0 0 0 .447-.32l.49-1.478c.141.179.24.386.24.621v1.412a.47.47 0 1 0 .941 0v-1.412a1.93 1.93 0 0 0-.461-1.224a2.4 2.4 0 0 0-.74-.611zm-9.957.085a.47.47 0 0 1 .669 0l2.353 2.353a.47.47 0 0 1 .014.65l-2.353 2.588a.47.47 0 0 1-.74-.057a7.3 7.3 0 0 1-.63-1.195a4.5 4.5 0 0 1-.39-1.652a4.1 4.1 0 0 1 1.082-2.682zm1.553 2.217l-1.18-1.182a3.3 3.3 0 0 0-.462 1.182zm-1.642.94c.056.264.15.547.263.82c.076.183.16.353.236.508l1.219-1.327z");
}

.i14sf2byk {
  fill: var(--svg-color--203a49, #203a49);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
