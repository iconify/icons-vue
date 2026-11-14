<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ii_upv31g"/><path class="ekiv6t8at"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cassette-player" /></template>
<style>
.ekiv6t8at {
  d: path("M4.75 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.205 2.037q.145-.068.278-.155t.253-.193t.224-.226q.103-.122.189-.256q.085-.135.151-.28t.11-.299q.045-.153.068-.311q.022-.158.022-.317q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148q-.085-.07-.177-.132q-.092-.061-.189-.113q-.098-.052-.2-.095q-.102-.042-.208-.074t-.214-.054q-.108-.021-.218-.032T15 7.75t-.221.011t-.218.032q-.108.022-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221q0 .154.021.307M7 12.25h5.7M15.5 15l6 3.25l-6 3.25Z");
}

.ii_upv31g {
  d: path("M12.7 17H2V4h18v10.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
