<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaiibmbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kids-haircut" /></template>
<style>
.iaiibmbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7.816 3.322Q10.287 16.5 10 16.5q-.111 0-.221.011t-.218.032t-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164q-.07.085-.132.177q-.061.092-.113.189q-.052.098-.095.2q-.042.102-.074.208t-.054.214q-.021.108-.032.218t-.011.221t.011.221t.032.218q.022.108.054.214t.074.208q.043.102.095.2q.052.097.113.189t.132.177t.148.164q.078.078.164.148q.085.07.177.132q.092.061.189.113q.098.052.2.095q.102.042.208.074t.214.054t.218.032T10 21t.221-.011t.218-.032t.214-.054q.106-.032.208-.074q.102-.043.2-.095q.097-.052.189-.113t.177-.132q.086-.07.164-.148t.148-.164q.07-.085.132-.177q.061-.092.113-.189q.052-.098.095-.2q.042-.102.074-.208t.054-.214t.032-.218t.011-.221q0-.338-.099-.661M7.25 12.75l8.684-1.421m3.356-.549L21 10.5m-9.958 3.56L13.5 3m4.25 11l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
