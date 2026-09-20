<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u9gzoptix"/><path class="qzfe7jbgc"/><path class="kxp8i0lhw"/><path class="d8dk38baw"/><path class="ext8p9bri"/><path class="wwi5rmbnq"/><path class="yzcx3ejdm"/><path class="dbv63gwne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:house" /></template>
<style>
.d8dk38baw {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M31 17a1 1 0 0 1-.707-.293L18 4.414L5.707 16.707a.999.999 0 1 1-1.414-1.414l13-13a1 1 0 0 1 1.414 0l13 13A.999.999 0 0 1 31 17");
}

.dbv63gwne {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M33.5 33.5A1.5 1.5 0 0 1 32 35H4a1.5 1.5 0 0 1 0-3h28a1.5 1.5 0 0 1 1.5 1.5");
}

.ext8p9bri {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M18 17a.999.999 0 0 1-.707-1.707l6.5-6.5a.999.999 0 1 1 1.414 1.414l-6.5 6.5A1 1 0 0 1 18 17");
}

.kxp8i0lhw {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M18 16h1v16h-1z");
}

.qzfe7jbgc {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M5 16L18 3l13 13v17H5z");
}

.u9gzoptix {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M9.344 14.702h-2a.5.5 0 0 1-.5-.5v-7a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-.5.5");
}

.wwi5rmbnq {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M10 26h4v6h-4z");
}

.yzcx3ejdm {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M10 17h4v4h-4zm12.5 0h4v4h-4zm0 9h4v4h-4z");
}

</style>
