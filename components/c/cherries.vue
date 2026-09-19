<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k20l8wbjf"/><path class="cqgfb2b-j"/><path class="snjwj-ibf"/><path class="olb66lbuy"/><path class="b32f91cbs"/><path class="w5tl8z88f"/><path class="uzyjdnb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cherries" /></template>
<style>
.b32f91cbs {
  fill: var(--svg-color--ce0f00, #ce0f00);
  d: path("M13.3 31.6c2.3.3 4.4.7 6.5.9c1.1.1 2.1.2 3.2.3s2.2.1 3.3.1c-1 .6-2.1.9-3.3 1.1c-1.1.2-2.3.2-3.4.1s-2.3-.4-3.3-.8c-1.1-.5-2.2-1-3-1.7");
}

.cqgfb2b-j {
  fill: none;
  stroke: var(--svg-color--83bf4f, #83bf4f);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M45.1 34C43 31.6 34.5 24 37.4 9");
}

.k20l8wbjf {
  fill: var(--svg-color--d33b23, #d33b23);
  d: path("M61 39.2c3.7 10.5-4.1 18.4-12.8 19.9c-8.7 1.4-18.4-3.6-18.8-14.7c-.6-14.7 10.1-13 13.9-13.6c6.3-1 13-5 17.7 8.4");
}

.olb66lbuy {
  fill: none;
  stroke: var(--svg-color--9fc427, #9fc427);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.4 33c0-4.1 6-25.5 34.1-30");
}

.snjwj-ibf {
  fill: var(--svg-color--ef4d3c, #ef4d3c);
  d: path("M38.5 42.2C40.7 54.5 30.4 62 20.4 62S.6 54.6 2.2 42.2C4.4 25.7 16 29.6 20.4 29.6c7.2-.1 15.4-3.3 18.1 12.6");
}

.uzyjdnb8c {
  fill: var(--svg-color--64892f, #64892f);
  d: path("M46.3 7.1c-3.8 8.9 9.3 21.2 9.3 21.2s-1.3-9.3 2.2-17.6C60.1 5.5 54.5 2 54.5 2s-6.3.6-8.2 5.1");
}

.w5tl8z88f {
  fill: var(--svg-color--a51000, #a51000);
  d: path("m38.5 34.8l5.6-1.3c.9-.2 1.8-.5 2.7-.7l2.8-.9c-.6.8-1.4 1.5-2.3 1.9c-.9.5-1.9.9-2.8 1.1c-1 .2-2 .4-3 .4c-1.1 0-2.1-.1-3-.5");
}

</style>
