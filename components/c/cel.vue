<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p6ucebb0b"><path class="rjqsgq_vj"/><path class="m2lzrjbrz"/><path class="fzs2ymcrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cel" /></template>
<style>
.fzs2ymcrm {
  d: path("M19.411 9.883a.53.53 0 1 0 0-1.059a.53.53 0 0 0 0 1.059");
}

.m2lzrjbrz {
  d: path("M19.412 10.942a1.588 1.588 0 1 0 0-3.176a1.588 1.588 0 0 0 0 3.176");
}

.p6ucebb0b {
  fill: var(--svg-color--4055a6, #4055a6);
}

.rjqsgq_vj {
  d: path("M17.633 5.912c.153.233.164.699-.074 1.043c-.244.344-.9.566-1.43.053c-1.382-1.334-3.5-1.594-4.49-1.594A6.61 6.61 0 0 0 4.838 12c.053 2.732 1.9 6.586 6.803 6.586c1.376 0 3.685-.593 4.85-1.81c.2-.212.92-.08 1.174.237c.26.318.186 1.06-.105 1.308a9.32 9.32 0 0 1-5.924 2.15C6.87 20.47 3 16.68 3 12s3.865-8.47 8.64-8.47c3.97 0 5.892 2.228 5.993 2.382");
}

</style>
