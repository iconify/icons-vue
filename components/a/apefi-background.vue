<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGTQHOTYis)" class="r4i437pya"/><path class="pmatc6cpy"/><path class="dirb6ubld"/></g><defs><linearGradient id="SVGTQHOTYis" x1="7.429" x2="16.443" y1="6.571" y2="18.337" gradientUnits="userSpaceOnUse"><stop class="z0ej23bum"/><stop offset=".24" class="recmq4bct"/><stop offset=".37" class="dd0_o-_2i"/><stop offset=".45" class="t97btubzk"/><stop offset=".53" class="eoxw9sb-t"/><stop offset=".8" class="cysuggbsy"/><stop offset=".97" class="j2ro9pbvg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apefi-background" /></template>
<style>
.cysuggbsy {
  stop-color: var(--svg-color--e7d9be, #e7d9be);
}

.dd0_o-_2i {
  stop-color: var(--svg-color--a99367, #a99367);
}

.dirb6ubld {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.94 7.765c.095-.094.438-.315.664-.315c.23 0 .419.221.513.315zM7.61 7.45c-.23 0-.315.221-.315.315H8c0-.094-.165-.315-.391-.315m.626.786c-.226 0-.47-.118-.47-.212l.94-.023c0 .094-.244.235-.47.235");
}

.eoxw9sb-t {
  stop-color: var(--svg-color--b8a070, #b8a070);
}

.ft5dv1b6b {
  fill: none;
}

.j2ro9pbvg {
  stop-color: var(--svg-color--d7c6a1, #d7c6a1);
}

.pmatc6cpy {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.337 19.942c.212-1.708.875-5.505 1.98-8.188c-.762.866-2.281 2.993-2.281 4.602c-.377-.673-1.2-2.357-1.426-3.736c-.282.861-.518 2.988.856 4.597l-.57 2.297l-3.425-2.01c.189-.287.57-.917.57-1.148c0-.287-.283-.574-.57-.287c.095-.673.57-2.3 1.713-3.449V9.458c0-.282.113-.917.57-1.148s1.331.48 1.712.861c-.188-.094-.687-.282-1.143-.282c-.457 0-.57.188-.57.282c.095.48.457 1.435 1.144 1.435c.682 0 1.426-.762 1.708-1.148c0-.315-.17-.931-.856-.86c.094-.095.343-.288.574-.288c.226 0 .856.188 1.138.287c.094-.094.283-.4.283-.861c0-.574-.283-1.148-.852-1.148c-.334 0-.668.292-.941.536c-.202.174-.367.325-.485.325c-.23 0-.668-.386-.856-.574C8.18 5.915 9.549 4 10.46 4c.65 0 1.3.932 1.897 1.788c.451.645.875 1.247 1.242 1.374c-.47.094-1.482.518-1.713 1.435c.287-.287 1.03-.861 1.713-.861c.856 0 2.851 1.148 2.851 2.01c0 .86.287 1.726 1.144 2.3c.447.301 1.247.617 1.934.857a9.56 9.56 0 0 1-4.216 5.693v-2.814c-.283.094-.97.861-1.426 3.157l-.104.424a9.4 9.4 0 0 1-4.446.579");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.recmq4bct {
  stop-color: var(--svg-color--cebc95, #cebc95);
}

.t97btubzk {
  stop-color: var(--svg-color--ae976a, #ae976a);
}

.z0ej23bum {
  stop-color: var(--svg-color--eae3d2, #eae3d2);
}

</style>
