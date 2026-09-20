<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ne_5t3atc"/><path class="hshinubbk"/><path class="xx22s488r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:area" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hshinubbk {
  fill: var(--svg-color--a0857c, #a0857c);
  d: path("m12 21l-4.264-6.632h2.131L12 17.94l2.132-3.572h2.131z");
}

.ne_5t3atc {
  fill: var(--svg-color--b8a874, #b8a874);
  d: path("M12 3L7.735 9.632h2.131L12 6.06l2.132 3.572h2.131z");
}

.xx22s488r {
  fill: var(--svg-color--a4a4a4, #a4a4a4);
  d: path("m7.026 11.053l-1.658 1.895h13.264l-1.658-1.895z");
}

</style>
