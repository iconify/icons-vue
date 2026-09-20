<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m3-_orher"/><ellipse class="y_ihjwy2v"/><ellipse class="vqtjp87sc"/><path class="ja-j--ezz"/><ellipse class="t_7qdabaz"/><path class="c17xa1q3a"/><path class="osn2r8j7a"/><path class="ytunzccyy"/><path class="rzm2iwpgq"/><path class="g04wjzbjk"/><path class="gi_ibqs-j"/><path class="lesmsx-ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:helicopter" /></template>
<style>
.c17xa1q3a {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M34.259 10c0-3 0-7-1-7s-3 4-4 6s5 1 5 1");
}

.g04wjzbjk {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M34.72 11.735c.909 1.279 1.28 2.575.83 2.894c-.45.32-1.553-.458-2.46-1.737c-.909-1.279-1.279-2.576-.829-2.896c.45-.318 1.551.46 2.459 1.739");
}

.gi_ibqs-j {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M33.076 9.419a1 1 0 1 1-1.632 1.158a1 1 0 0 1 1.632-1.158");
}

.ja-j--ezz {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M12.26 3h2v6h-2z");
}

.lesmsx-ju {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M25.26 32a2 2 0 0 1-2 2h-20a2 2 0 0 1 0-4h20a2 2 0 0 1 2 2");
}

.m3-_orher {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M16.26 26h2v5h-2zm-8 0h2v5h-2z");
}

.osn2r8j7a {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M34.259 10c0-2.209-8-3-19-3h-2C6.632 7 .509 12.451.509 18.25S4.259 28 13.259 28s12-4.701 12-10.5c0-.881-.138-1.731-.371-2.549C29.259 14 34.259 12.006 34.259 10");
}

.rzm2iwpgq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M31.441 7.114c.903 1.273 1.271 2.564.82 2.884s-1.548-.454-2.451-1.726s-1.271-2.564-.82-2.884c.45-.321 1.547.453 2.451 1.726");
}

.t_7qdabaz {
  cx: 13.259px;
  cy: 3px;
  fill: var(--svg-color--66757f, #66757f);
  rx: 2px;
  ry: 1px;
}

.vqtjp87sc {
  cx: 20.259px;
  cy: 3px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 6px;
  ry: 1px;
}

.y_ihjwy2v {
  cx: 6.259px;
  cy: 3px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 6px;
  ry: 1px;
}

.ytunzccyy {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M4.259 13c-2.091 2.918-3.068 7.589 1.213 7.784c4.787.216 6.787.216 7.85-2.372c1.364-3.32.937-7.413-.276-8.195c-2.32-1.497-6.695-.135-8.787 2.783m16.841-.465C23.259 16 23.17 18.696 19.259 20c-3 1-4-2-3.841-5.535c.112-2.483.206-4.195 1.841-4.465c1.447-.24 2.526.426 3.841 2.535");
}

</style>
