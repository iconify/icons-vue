<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cslzoyu9y"/><path class="in0vui44b"/><path class="o2-by7b-y"/><path class="s2ndkqb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-gcloud" /></template>
<style>
.cslzoyu9y {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M19.77 10.94h.85l2.44-2.44l.11-1a10.92 10.92 0 0 0-17.79 5.31a1.3 1.3 0 0 1 .85-.05L11.1 12s.25-.41.37-.38a6.06 6.06 0 0 1 8.31-.63Z");
}

.in0vui44b {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M26.52 12.81a11 11 0 0 0-3.3-5.33L19.8 10.9a6 6 0 0 1 2.2 4.81v.61a3 3 0 0 1 0 6.08h-6l-.61.61v3.65l.61.61h6a7.91 7.91 0 0 0 4.49-14.46Z");
}

.o2-by7b-y {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M9.86 27.23h6.08v-4.87H9.86a3 3 0 0 1-1.25-.27l-.86.27l-2.45 2.43l-.21.85a7.82 7.82 0 0 0 4.77 1.59");
}

.s2ndkqb3n {
  fill: var(--svg-color--fbbc05, #fbbc05);
  d: path("M9.86 11.44a7.91 7.91 0 0 0-4.77 14.18l3.52-3.53a3 3 0 1 1 4-4l3.52-3.53a7.9 7.9 0 0 0-6.27-3.12");
}

</style>
