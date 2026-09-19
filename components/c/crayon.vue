<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sc3_b8bag"/><path class="bolpsq29n"/><path class="eswibvblt"/><path class="eaj1zdkap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:crayon" /></template>
<style>
.bolpsq29n {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M21.6 55.2c-1.2 1.2-3.1 1.1-4.3-.1l-8.4-8.4c-1.2-1.2-1.2-3.1-.1-4.3L48.3 2.9c1.2-1.2 3.1-1.1 4.3.1l8.4 8.4c1.2 1.2 1.2 3.1.1 4.3z");
}

.eaj1zdkap {
  fill: var(--svg-color--52c18e, #52c18e);
  d: path("m38.694 12.556l3.253-3.252l12.798 12.798l-3.252 3.253zM15.18 36.01l3.253-3.252l12.799 12.799l-3.253 3.252zM35 29c-4.3 4.3-10.7 4.9-14.2 1.4l15.6-15.6c3.5 3.6 2.9 9.9-1.4 14.2");
}

.eswibvblt {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M11.982 39.238L45.145 6.075l12.799 12.799L24.78 52.037z");
}

.sc3_b8bag {
  fill: var(--svg-color--71ad3e, #71ad3e);
  d: path("m18.3 51.7l-6.1-6.1c-.9-.9-2.2-.8-2.9.3L2.4 57.6c-.7 1.1-.5 2.7.4 3.6s2.5 1 3.6.4L18 54.7c1.1-.7 1.3-2 .3-3");
}

</style>
