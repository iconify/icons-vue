<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mybkk9skk"/><path class="bkxr_3jwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lym" /></template>
<style>
.bkxr_3jwe {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.522 16.127l3.876-6.505S14.707 9 15.682 9h4.111s1.704.036 1.062 1.137c-.642 1.114-4.543 7.68-4.543 7.68s-.259.682-1.309.682H9.992s-.926-.036-.235-1.15s.766-1.222.766-1.222");
}

.ft5dv1b6b {
  fill: none;
}

.mybkk9skk {
  fill: var(--svg-color--fdc5ca, #fdc5ca);
  d: path("M9.315 17.72L3.062 6.769c.012 0-.456-1.265 1.008-1.265h4.033a1.33 1.33 0 0 1 1.224.633C9.77 6.866 16 17.83 16 17.83l-5.353.669a1.43 1.43 0 0 1-1.332-.778");
}

</style>
