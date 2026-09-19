<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d245zxgwh"/><path class="njmok7f2v"/><path class="u7es78bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-armenia" /></template>
<style>
.d245zxgwh {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.njmok7f2v {
  fill: var(--svg-color--f2b200, #f2b200);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.u7es78bok {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

</style>
