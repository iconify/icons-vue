<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fl7o7rbpm"/><path class="jftx9rb0l"/><path class="gd4_-1bej"/><circle class="ikz1dibhx"/><path class="yzo2sppya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-north-korea" /></template>
<style>
.fl7o7rbpm {
  fill: var(--svg-color--024fa2, #024fa2);
  d: path("M54 11H10c-5.491 0-8.74 3.385-9.695 8h63.39c-.956-4.615-4.205-8-9.696-8M10 55h44c5.881 0 9.193-3.881 9.865-9H.135c.672 5.119 3.984 9 9.865 9");
}

.gd4_-1bej {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 44c0 .684.049 1.351.135 2h63.73c.086-.649.135-1.316.135-2zm63.965-23a14 14 0 0 0-.27-2H.305a14 14 0 0 0-.27 2z");
}

.ikz1dibhx {
  cx: 19.393px;
  cy: 32.393px;
  r: 8.893px;
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

.jftx9rb0l {
  fill: var(--svg-color--ed1c27, #ed1c27);
  d: path("M0 22v22h64V22c0-.338-.015-.67-.035-1H.035c-.02.33-.035.662-.035 1");
}

.yzo2sppya {
  fill: var(--svg-color--ed1c27, #ed1c27);
  d: path("m26.803 30.08l-5.693.01l-1.765-5.757l-1.754 5.757l-5.696-.01l4.615 3.51l-1.791 5.72l4.635-3.554l4.635 3.554l-1.789-5.72z");
}

</style>
