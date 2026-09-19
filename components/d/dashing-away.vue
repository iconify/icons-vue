<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ai6_cpbiv"><ellipse class="doo91db-w"/><ellipse class="vrrt4t2aj"/><ellipse class="dclkoxf5v"/><ellipse class="r3ulox3ns"/><ellipse class="hvsverb7e"/><ellipse class="yk03gobio"/><ellipse class="fwcfr_ntm"/><path class="y2m-48bbe"/><path class="akxatk7cf"/><path class="x96y50b9a"/></g><g class="n1mjunbsu"><path class="jl29qwb_t"/><path class="b2vechbvy"/><path class="tak60vswg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dashing-away" /></template>
<style>
.ai6_cpbiv {
  fill: var(--svg-color--7ca7bf, #7ca7bf);
}

.akxatk7cf {
  d: path("M2 32.2c3.8-.3 7.4-1.1 11.1-2c1.8-.5 3.6-1 5.4-1.6s3.6-1.2 5.3-1.9c1.8-.7 3.6.7 4.1 3.1c.5 2.5-.5 5-2.2 5.8c-.3.1-.6.2-.9.2c-2 0-3.9-.1-5.8-.3s-3.8-.4-5.7-.7c-3.9-.6-7.6-1.4-11.3-2.6m5.2 10.3c2.8-1 5.7-1.7 8.6-2.2c1.5-.3 2.9-.5 4.4-.8c1.5-.2 2.9-.4 4.4-.6c1.8-.2 3.4 1.8 3.6 4.3c.1 2.6-1.3 4.8-3.1 5c-.4 0-.9 0-1.2-.2c-1.3-.6-2.7-1.1-4.1-1.7l-4.2-1.5c-2.7-.9-5.5-1.7-8.4-2.3");
}

.b2vechbvy {
  d: path("M34.5 16c2.2 2.3 3.5 5.3 3.9 8.6c1.9-4.1 1.6-8.6-1-11.3c-2.5-2.7-6.6-3-10.4-1.2c2.8.4 5.4 1.7 7.5 3.9m18.2 1.5c1.4 1.5 2.3 3.5 2.5 5.6c1.2-2.7 1.1-5.6-.7-7.4c-1.7-1.7-4.3-2-6.8-.8c2 .4 3.7 1.2 5 2.6M35.3 37.6c2.1 2.2 3.3 5 3.6 8c1.7-3.8 1.5-8-.9-10.6c-2.4-2.5-6.2-2.8-9.7-1.2c2.6.6 5.1 1.8 7 3.8m19.4-6.9c2.2 2.3 3.5 5.3 3.9 8.6c1.9-4.1 1.6-8.6-1-11.3c-2.5-2.7-6.6-3-10.4-1.2c2.8.4 5.4 1.7 7.5 3.9");
}

.dclkoxf5v {
  cx: 43.8px;
  cy: 47.1px;
  rx: 11.5px;
  ry: 12.9px;
}

.doo91db-w {
  cx: 51.5px;
  cy: 34.6px;
  rx: 10.5px;
  ry: 11.8px;
}

.fwcfr_ntm {
  cx: 30.7px;
  cy: 20.8px;
  rx: 10.3px;
  ry: 11.5px;
}

.hvsverb7e {
  cx: 41.6px;
  cy: 15.1px;
  rx: 9.9px;
  ry: 11.1px;
}

.jl29qwb_t {
  d: path("M42.9 29.1c3.6 3.7 5.6 8.6 6.2 13.9c3-6.6 2.6-13.8-1.6-18.2c-4.1-4.3-10.7-4.8-16.8-2c4.7.8 8.9 2.9 12.2 6.3");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.r3ulox3ns {
  cx: 39.6px;
  cy: 29.8px;
  rx: 9.9px;
  ry: 11.1px;
}

.tak60vswg {
  d: path("M44.3 11.6c2.2 2.3 3.5 5.3 3.9 8.6c1.9-4.1 1.6-8.6-1-11.3c-2.5-2.7-6.6-3-10.4-1.2c2.9.5 5.5 1.8 7.5 3.9");
}

.vrrt4t2aj {
  cx: 30.7px;
  cy: 42.4px;
  rx: 9.8px;
  ry: 11px;
}

.x96y50b9a {
  d: path("M2 37.7q5.55-1.8 11.1-3c1.9-.4 3.7-.8 5.6-1.1l5.7-.9c1.8-.2 3.4 1.7 3.6 4.2s-1.2 4.8-3 5c-.3 0-.7 0-1-.1c-1.8-.5-3.6-1-5.4-1.4s-3.7-.8-5.5-1.2c-3.6-.6-7.4-1.1-11.1-1.5");
}

.y2m-48bbe {
  d: path("M7.2 27.4c2.9-.6 5.7-1.6 8.4-2.7c1.4-.6 2.7-1.2 4.1-1.9c1.3-.7 2.7-1.4 3.9-2.1c1.7-1 3.7 0 4.4 2.4s0 5.1-1.7 6.2c-.4.2-.8.4-1.2.4H25c-1.6.1-3 0-4.6 0l-4.5-.3c-2.9-.5-5.9-1-8.7-2");
}

.yk03gobio {
  cx: 50.4px;
  cy: 20.8px;
  rx: 8px;
  ry: 9px;
}

</style>
