<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVG1x9sAb7O" cx="0" cy="0" r="1" gradientTransform="matrix(-.484 30.7 -26.2 -.413 11.3 15.6)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".34" class="vc--wpv5i"/><stop offset=".51" class="t194c-bqg"/><stop offset=".75" class="r16ifwbgy"/><stop offset=".87" class="eouhdjbue"/><stop offset="1" class="t021yu__t"/></radialGradient><radialGradient id="SVG35MzwcIS" cx="0" cy="0" r="1" gradientTransform="matrix(3.53 0 0 2.71 19.4 14.8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".34" class="vc--wpv5i"/><stop offset=".51" class="t194c-bqg"/><stop offset=".75" class="r16ifwbgy"/><stop offset=".87" class="eouhdjbue"/><stop offset="1" class="t021yu__t"/></radialGradient><linearGradient id="SVGdCJ5Je4U" x2="1" gradientTransform="rotate(257.4 22.26 3.182)scale(18.24)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".34" class="vc--wpv5i"/><stop offset=".51" class="t194c-bqg"/><stop offset=".75" class="r16ifwbgy"/><stop offset=".87" class="eouhdjbue"/><stop offset="1" class="t021yu__t"/></linearGradient><linearGradient id="SVG2tSfteIO" x2="1" gradientTransform="rotate(79.2 26.768 -14.151)scale(70)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".34" class="vc--wpv5i"/><stop offset=".51" class="s6pqz_u9i"/><stop offset=".75" class="oyrwup1az"/><stop offset=".87" class="eouhdjbue"/><stop offset="1" class="t021yu__t"/></linearGradient></defs><path class="dz2gj2bes"/><path class="wpjp7226u"/><path fill="url(#SVG2tSfteIO)" clip-rule="evenodd" class="xlf2iig6l"/><path fill="url(#SVGdCJ5Je4U)" clip-rule="evenodd" class="g8011nbcq"/><path fill="url(#SVG35MzwcIS)" clip-rule="evenodd" class="y9m_pebeo"/><path fill="url(#SVG1x9sAb7O)" clip-rule="evenodd" class="aisk5dltp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-gentoo-opened" /></template>
<style>
.aisk5dltp {
  fill-rule: evenodd;
  d: path("M18.7 10.6c-2.04.215-2.43.477-4.28 1.88c-.619.468-1.76 1.61-2.05 2.96c-.111.515.02.96.391 1.27c1.19.998 3.18 1.81 4.81 2.59c.478.229.161.645-.609 1.31c-1.94 1.68-4.57 3.73-4.76 5.29c-.087.735.165 1.73 1.06 2.25c1.04.597 3.21.208 4.65-.331c2.11-.787 4.89-2.52 7.09-4.23c2.29-1.77 4.42-4.03 4.53-4.4a1.7 1.7 0 0 0-.133-1.35c-.392-.753-.916-1.31-1.48-1.94c-1.51-1.59-3.11-2.99-5.02-4.06c-1.38-.774-2.6-1.41-4.2-1.24zm3 3.57c1.47.712 2.99 2.58-.013 3.66c-.816.293-3.4-.719-3.32-2.1c.115-2.04 1.54-2.43 3.34-1.56z");
}

.dz2gj2bes {
  fill: var(--svg-color--877adc, #877adc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.eouhdjbue {
  stop-color: var(--svg-color--9f99c7, #9f99c7);
}

.g8011nbcq {
  fill-rule: evenodd;
  d: path("M16.9 20c-1.03.872-1.72 1.46-2.58 2.25c-2.07 1.9-3.48 3.34-2.76 5.31c.838 2.28 2.68 2.16 4.83 1.74c5.55-1.1 14.7-8.11 14.2-10.7c-.377-2.1-5.48-6.27-8.5-7.75a6.44 6.44 0 0 0-3.12-.652c-4.15.196-7.4 3.98-7.23 6.03c.161 1.99 5.2 3.73 5.14 3.79zm-.623-6.96c-1.25 1.39-.451 4.08 1.62 5.55c2.42 1.72 6.35 2.03 7.13.703c1.46-2.47-.134-5.08-2.51-6.24c-2.35-1.15-5.47-.875-6.24-.008z");
}

.oyrwup1az {
  stop-color: var(--svg-color--867fb7, #867fb7);
}

.r16ifwbgy {
  stop-color: var(--svg-color--928bbe, #928bbe);
}

.s6pqz_u9i {
  stop-color: var(--svg-color--bebdf3, #bebdf3);
}

.t021yu__t {
  stop-color: var(--svg-color--524c76, #524c76);
}

.t194c-bqg {
  stop-color: var(--svg-color--bebbdb, #bebbdb);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wpjp7226u {
  fill: var(--svg-color--877adc, #877adc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.xlf2iig6l {
  fill-rule: evenodd;
  d: path("M11 26.8c.002-.883.753-2.12 1.82-3.24c.713-.749 1.44-1.41 3.02-2.75c-1.09-.599-2.79-1.32-3.64-2.27c-.315-.35-.887-1.14-.776-2.2c.226-2.16 2.89-5.44 6.68-6.13a6.83 6.83 0 0 1 3.9.472c3.74 1.68 8.31 5.86 8.87 7.9c.198.718.16 1.86-.181 2.5c-.423.79-1.89 2.4-3.89 4.05c-3.14 2.6-7.55 5.39-10.8 5.86c-1.06.152-2.15-.006-2.91-.437c-1.19-.673-1.59-1.57-1.73-1.84c-.37-.716-.324-1.62-.323-1.91zm8.85-9.92c.04-.501 2-.002 1.88.394c-.131.418-1.93.18-1.88-.394");
}

.y9m_pebeo {
  fill-rule: evenodd;
  d: path("M20.5 18.5c1.75.244 3.27-.459 3.5-2.19c.18-1.32-1.84-2.76-3.05-3.09c-1.01-.278-3.22.08-3.36 2c-.154 1.99 1.89 3.15 2.91 3.29zm-.859-3.32c-1.15 1.79 1.67 2.34 2.11 2.01c1.87-1.4-1.6-2.8-2.11-2.01");
}

</style>
