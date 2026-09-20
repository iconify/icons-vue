<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="rdad5rciw"/><path class="zxy9t5bul"/><path clip-rule="evenodd" class="f7bpir_fn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ari" /></template>
<style>
.f7bpir_fn {
  fill: var(--svg-color--febb02, #febb02);
  fill-rule: evenodd;
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0 1a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.rdad5rciw {
  cx: 12px;
  cy: 12px;
  r: 9px;
  fill: var(--svg-color--fff, #fff);
}

.zxy9t5bul {
  fill: var(--svg-color--202451, #202451);
  d: path("M7.464 13.542a.1.1 0 0 0 .098-.051l1.404-2.674a.103.103 0 0 1 .185 0l1.404 2.674a.11.11 0 0 0 .098.051h.36a.106.106 0 0 0 .092-.154L9.321 9.994a.1.1 0 0 0-.093-.051h-.34a.1.1 0 0 0-.092.051l-1.784 3.394a.106.106 0 0 0 .097.154h.36zm6.223-3.6h-1.955a.103.103 0 0 0-.102.104v3.393c0 .057.046.103.102.103h.309a.103.103 0 0 0 .103-.103v-2.982h1.543c.252 0 .514.298.514.514c0 .345-.175.514-.514.514h-.7a.103.103 0 0 0-.103.103v.376c0 .02.01.046.026.066l1.214 1.476a.1.1 0 0 0 .077.036h.411c.088 0 .134-.103.082-.164l-1.07-1.379c.608 0 1.09-.406 1.09-1.028c0-.54-.513-1.028-1.027-1.028m2.16 3.6a.1.1 0 0 1-.104-.103v-3.393c0-.057.047-.103.103-.103h.309c.056 0 .103.046.103.103v3.393a.1.1 0 0 1-.103.103z");
}

</style>
