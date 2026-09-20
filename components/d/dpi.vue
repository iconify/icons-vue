<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uyr1fy6tq"/><path class="fl28m6w_m"/><path class="brnwmli1p"/><path class="i3fy-ib2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dpi" /></template>
<style>
.brnwmli1p {
  fill: var(--svg-color--9b74ec, #9b74ec);
  d: path("M14.537 7.625a5.1 5.1 0 0 0-1.17-1.762a4.7 4.7 0 0 0-2.062-1.169c.482.79.75 1.69.78 2.614c.28.283.55 2.49.72 2.913L7.494 13.89v-.945c-.614.051-1.22 0-1.838-.008v2.77h3.85a5.68 5.68 0 0 0 3.667-1.38a5.3 5.3 0 0 0 1.296-1.754a5.8 5.8 0 0 0 .504-2.507c0-.958-.144-1.737-.436-2.44");
}

.fl28m6w_m {
  fill: var(--svg-color--6b42bd, #6b42bd);
  d: path("M7.773 13.046V6.39h1.483c.511.004 1.02.085 1.507.241a3.44 3.44 0 0 1 1.373.843c.004-.89-.318-1.779-.776-2.584a5.7 5.7 0 0 0-1.558-.216H5.656v8.365c.61.008 1.507.059 2.117.008");
}

.ft5dv1b6b {
  fill: none;
}

.i3fy-ib2e {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.317 12.317c.597 0 1.228-.097 1.757-.241c.49-.147.945-.39 1.338-.716c.4-.304.72-.7.932-1.156c.233-.474.348-1.046.348-1.724c0-.669-.102-1.186-.305-1.668a3 3 0 0 0-.848-1.16a3.8 3.8 0 0 0-1.32-.73a5.6 5.6 0 0 0-1.585-.228H5.656v7.623zM3.962 3h4.252c.712 0 1.398.11 2.059.339c.66.22 1.245.563 1.753 1.02a5 5 0 0 1 1.22 1.728a5.8 5.8 0 0 1 .457 2.393q.001 1.419-.525 2.457a5.25 5.25 0 0 1-1.355 1.723a5.7 5.7 0 0 1-1.847 1.017c-.677.224-1.126.334-1.779.334H3.962z");
}

.uyr1fy6tq {
  fill: var(--svg-color--3c176b, #3c176b);
  d: path("m20.033 12.585l-8.44-8.335l-4.811-.902l-2.817 10.63L11.076 21a11.89 11.89 0 0 0 8.962-8.415z");
}

</style>
