<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG70fyBe1h" x1="-117.555" x2="-116.883" y1="260.894" y2="260.894" gradientTransform="rotate(90 2089.825 5520.838)scale(29.091)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="SVGBNnuudGc" x1="-117.555" x2="-116.883" y1="261.146" y2="261.146" href="#SVG70fyBe1h"/><mask id="SVGd5gWwdIP" width="19.545" height="19.546" x="11.227" y="11.227" maskUnits="userSpaceOnUse"><path class="au1th7bdi"/></mask></defs><path class="v8qal1b1e"/><g mask="url(#SVGd5gWwdIP)"><path class="cgml6j58l"/><path class="bslsqobus"/><path class="tjrku9bgn"/><path class="tlcc2nbaw"/><path class="ibfgydbak"/><path class="i_g6nybgv"/><path class="twkgc7bsc"/><path class="s0pwigg0x"/><path class="mpv30dtmf"/><g class="xyjtgccot"><path fill="url(#SVG70fyBe1h)" class="biexqvb_j"/><path fill="url(#SVGBNnuudGc)" class="ezgnfobnk"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-azurepipelines" /></template>
<style>
.au1th7bdi {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.08 24.342l.983-1.052l1.222 1.222l-1 .994l1.205 1.2l.993-.994l1.229 1.23l-.974.973l2.85 2.85h4.48a.814.814 0 0 0 .814-.814v-6.512l4.162-2.775a1.63 1.63 0 0 0 .724-1.354v-7.269a.814.814 0 0 0-.814-.814h-7.268a1.63 1.63 0 0 0-1.355.724l-2.774 4.162H12.04a.814.814 0 0 0-.812.815v4.479Zm-1.387 1.544h-1.465v4.887h4.885v-1.466h-3.42Z");
}

.biexqvb_j {
  d: path("m14.08 24.342l.983-1.052l1.222 1.222l-1 .994l1.205 1.2l.993-.994l1.229 1.23l-.974.973l2.85 2.85h4.48a.814.814 0 0 0 .814-.814v-6.512l4.162-2.775a1.63 1.63 0 0 0 .724-1.354v-7.269a.814.814 0 0 0-.814-.814h-7.268a1.63 1.63 0 0 0-1.355.724l-2.774 4.162H12.04a.814.814 0 0 0-.812.815v4.479Z");
}

.bslsqobus {
  fill: var(--svg-color--0f46bd, #0f46bd);
  d: path("M11.228 16.927v4.48l2.852 2.935l1.22-1.307l3.664 3.665l-1.222 1.22l2.85 2.85h4.48a.814.814 0 0 0 .814-.814v-6.517l-7.329-7.326H12.04a.813.813 0 0 0-.812.814");
}

.cgml6j58l {
  fill: var(--svg-color--91b0f2, #91b0f2);
  d: path("M11.228 25.886h1.465v3.421h3.42v1.466h-4.885Z");
}

.ezgnfobnk {
  d: path("M12.693 25.886h-1.465v4.887h4.885v-1.466h-3.42Z");
}

.i_g6nybgv {
  fill: var(--svg-color--729af2, #729af2);
  d: path("m15.289 25.506l6.218-6.218l1.2 1.2l-6.217 6.219Z");
}

.ibfgydbak {
  fill: var(--svg-color--0a44c2, #0a44c2);
  d: path("m15.289 25.506l6.218-6.218l1.2 1.2l-6.217 6.219Z");
}

.mpv30dtmf {
  fill: var(--svg-color--91b0f2, #91b0f2);
  d: path("M25.887 18.557a2.443 2.443 0 1 0-2.443-2.443a2.443 2.443 0 0 0 2.443 2.443");
}

.s0pwigg0x {
  fill: var(--svg-color--0a44c2, #0a44c2);
  d: path("M25.887 18.557a2.443 2.443 0 1 0-2.443-2.443a2.443 2.443 0 0 0 2.443 2.443");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tjrku9bgn {
  fill: var(--svg-color--062aa9, #062aa9);
  d: path("m14.281 22.511l7.533-11.284h8.959v8.958l-11.284 7.533Z");
}

.tlcc2nbaw {
  fill: var(--svg-color--2560e0, #2560e0);
  d: path("M14.752 22.983a.814.814 0 0 1-.1-1.028l6.679-10a1.63 1.63 0 0 1 1.354-.724h7.275a.815.815 0 0 1 .815.814v7.274a1.63 1.63 0 0 1-.725 1.354l-10 6.679a.815.815 0 0 1-1.028-.1Z");
}

.twkgc7bsc {
  fill: var(--svg-color--4c80f0, #4c80f0);
  d: path("m17.487 25.716l-1.2-1.2l5.225-5.224l1.2 1.2Z");
}

.v8qal1b1e {
  fill: var(--svg-color--7798cc, #7798cc);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xyjtgccot {
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
