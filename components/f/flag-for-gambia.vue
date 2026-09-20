<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="woswaf1ph"/><path class="x-g_wsb6g"/><path class="dvi175hsx"/><path class="ej6l_4bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-gambia" /></template>
<style>
.dvi175hsx {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 21h36v2H0zm0-8h36v2H0z");
}

.ej6l_4bmk {
  fill: var(--svg-color--0d218a, #0d218a);
  d: path("M0 15h36v6H0z");
}

.woswaf1ph {
  fill: var(--svg-color--cc162b, #cc162b);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.x-g_wsb6g {
  fill: var(--svg-color--3c762c, #3c762c);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4H0z");
}

</style>
