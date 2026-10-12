<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dha1hlpfj"/><circle class="gpj5lihjv"/><path class="igj8aovuh"/><path class="pvi3c1b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cathedral-sharp" /></template>
<style>
.dha1hlpfj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V8l.22-.56l1.56-3.88l.22-.56l.22.56l1.56 3.88l.22.56v3l.49-.35l4.27-3.05l.49-.35l.49.35l4.27 3.05l.49.35V8l.22-.56l1.56-3.88l.22-.56l.22.56l1.56 3.88l.22.56v13.25H2.75z");
}

.gpj5lihjv {
  cx: 12px;
  cy: 12.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igj8aovuh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25V17h3.5v4.25");
}

.pvi3c1b4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 12.5h.01m14.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
