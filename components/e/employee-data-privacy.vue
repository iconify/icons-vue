<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rims_gb7c"/><path class="h41q028nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employee-data-privacy" /></template>
<style>
.h41q028nz {
  d: path("M6.21 12.656q-.11.078-.211.168t-.19.192t-.166.213q-.076.112-.139.232q-.062.12-.11.246q-.047.127-.079.258q-.033.131-.049.266q-.016.134-.016.269q0 .111.011.221t.032.218q.022.108.054.214t.074.208q.043.102.095.2q.052.097.113.189t.132.177t.148.164t.164.148q.085.07.177.132q.092.061.189.113q.098.052.2.095q.102.042.208.074t.214.054t.218.032t.221.011t.221-.011t.218-.032t.214-.054q.106-.032.208-.074q.102-.043.2-.095q.097-.052.189-.113t.177-.132q.086-.07.164-.148t.148-.164t.132-.177q.061-.092.113-.189q.052-.098.095-.2q.042-.102.074-.208t.054-.214t.032-.218t.011-.221q0-.243-.052-.481q-.052-.237-.153-.458t-.248-.415t-.331-.352M12.5 13h6.25m-6.25 3.25H17M9 4.5h6V10H9Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1M12 7.25h.01");
}

.rims_gb7c {
  d: path("M17.8 7.5h3.7V21h-19V7.5h3.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
