<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="f124h_b3v"><path class="nu7mtno3q"/><path clip-rule="evenodd" class="l7j_rh3bu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cbbtc" /></template>
<style>
.f124h_b3v {
  fill: var(--svg-color--0052ff, #0052ff);
}

.l7j_rh3bu {
  fill-rule: evenodd;
  d: path("M12 20.156a8.156 8.156 0 1 0 0-16.312a8.156 8.156 0 0 0 0 16.312M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.nu7mtno3q {
  d: path("M15.956 10.886c.176-1.179-.723-1.812-1.949-2.235l.397-1.598l-.972-.242l-.387 1.555a34 34 0 0 0-.78-.183l.392-1.565l-.972-.243l-.398 1.598a28 28 0 0 1-.622-.147l.002-.005l-1.341-.336l-.259 1.04s.721.164.706.174c.393.1.465.36.453.566l-.453 1.82q.052.014.1.033l-.102-.026l-.636 2.55c-.048.119-.17.299-.446.23a15 15 0 0 1-.706-.175L7.5 14.809l1.266.315l.693.179l-.403 1.616l.972.241l.398-1.597q.396.107.774.2l-.396 1.59l.972.243l.402-1.612c1.658.315 2.904.188 3.43-1.312c.422-1.207-.022-1.905-.895-2.358c.636-.146 1.114-.565 1.243-1.428m-2.222 3.115c-.3 1.208-2.334.555-2.993.392l.534-2.141c.66.164 2.772.49 2.459 1.75m.301-3.132c-.274 1.098-1.966.54-2.514.403l.483-1.94c.548.136 2.317.391 2.031 1.537");
}

</style>
