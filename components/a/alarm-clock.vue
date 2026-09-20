<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dyop_uraa"/><path class="plnhd19zb"/><path class="q43k6ubsr"/><path class="kmaotwgjx"/><path class="buvp7-bsl"/><path class="z0li2yb3a"/><path class="oez55f7jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:alarm-clock" /></template>
<style>
.buvp7-bsl {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M30.041 19.385c0 6.674-5.335 12.084-11.92 12.084c-6.583 0-11.919-5.41-11.919-12.084C6.202 12.71 11.538 7.3 18.121 7.3c6.585-.001 11.92 5.41 11.92 12.085");
}

.dyop_uraa {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M20 6.042c0 1.112-.903 2.014-2 2.014s-2-.902-2-2.014V2.014C16 .901 16.903 0 18 0s2 .901 2 2.014z");
}

.kmaotwgjx {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M34.015 19.385c0 8.898-7.115 16.111-15.894 16.111c-8.777 0-15.893-7.213-15.893-16.111c0-8.9 7.116-16.113 15.893-16.113c8.778-.001 15.894 7.213 15.894 16.113");
}

.oez55f7jc {
  fill: var(--svg-color--414042, #414042);
  d: path("M23 20h-5a1 1 0 0 1-1-1v-9a1 1 0 0 1 2 0v8h4a1 1 0 1 1 0 2");
}

.plnhd19zb {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M9.18 36c-.224 0-.452-.052-.666-.159a1.52 1.52 0 0 1-.667-2.027l8.94-18.127c.252-.512.768-.835 1.333-.835s1.081.323 1.333.835l8.941 18.127a1.52 1.52 0 0 1-.666 2.027a1.48 1.48 0 0 1-1.999-.676L18.121 19.74l-7.607 15.425A1.49 1.49 0 0 1 9.18 36");
}

.q43k6ubsr {
  fill: var(--svg-color--58595b, #58595b);
  d: path("M18.121 20.392a1 1 0 0 1-.702-.295L3.512 5.998c-.388-.394-.388-1.031 0-1.424s1.017-.393 1.404 0L18.121 17.96L31.324 4.573a.985.985 0 0 1 1.405 0a1.017 1.017 0 0 1 0 1.424l-13.905 14.1a1 1 0 0 1-.703.295");
}

.z0li2yb3a {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M30.04 1.257a5.9 5.9 0 0 0-4.214 1.77l8.429 8.544A6.06 6.06 0 0 0 36 7.299c0-3.336-2.669-6.042-5.96-6.042m-24.08 0a5.9 5.9 0 0 1 4.214 1.77l-8.429 8.544A6.06 6.06 0 0 1 0 7.299c0-3.336 2.668-6.042 5.96-6.042");
}

</style>
