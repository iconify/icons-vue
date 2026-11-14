<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n4s88kbew"/><path class="g1tu8toma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gps-signal-lost" /></template>
<style>
.g1tu8toma {
  d: path("M14.326 10.417q.174-.442.174-.917q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231q-.047-.113-.105-.221q-.058-.109-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06t-.243-.036T12 7q-.457 0-.884.162M3.5 3.5l17 17");
}

.n4s88kbew {
  d: path("M14.437 18.463c-.874.974-1.734 1.834-2.437 2.537c-2.5-2.5-7-7-7-11.5q0-.262.02-.523m2.788-5.083q.451-.337.95-.598t1.033-.438t1.09-.268T12 2.5q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184t.281.198t.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343Q19 9.328 19 9.5c0 1.456-.471 2.912-1.193 4.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
