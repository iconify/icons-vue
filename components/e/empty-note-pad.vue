<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z_lw1mblg"/><path class="syvgehb4o"/><path class="vhtbr-7tr"/><path class="c_fv22-ca"/><path class="zxn34rbad"/><path class="pw4_dbcry"/><path class="n21-87ozn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:empty-note-pad" /></template>
<style>
.c_fv22-ca {
  fill: var(--svg-color--ad9a28, #ad9a28);
  d: path("M15.507 2.436s-11.263 40.03-13.28 41.34C.217 45.088 51 52.552 51 52.552s8.429-42.4 8.526-43.41c.103-1.01-44.02-6.714-44.02-6.714");
}

.n21-87ozn {
  fill: var(--svg-color--fff200, #fff200);
  d: path("M14.406 1S3.567 34.03 1.549 35.35c-2.02 1.312 37.879 17.09 42.07 13.211c1.813-1.677 6.04-9.03 8.874-15.934c4.802-11.696 7.422-23 7.482-23.623c.102-1.01-45.573-8-45.573-8");
}

.pw4_dbcry {
  fill: var(--svg-color--e8d807, #e8d807);
  d: path("M14.406 1S2.076 38.476.06 39.784c-2.02 1.312 47.695 13.186 50.22 10.728s9.601-40.499 9.703-41.509s-45.573-8-45.573-8");
}

.syvgehb4o {
  fill: var(--svg-color--e8d807, #e8d807);
  d: path("m3.988 48.46l3.562 5.531l48.14 7.712l-4.246-6.623z");
}

.vhtbr-7tr {
  fill: var(--svg-color--eddc0a, #eddc0a);
  d: path("M14.406 1S4.862 45.37 2.842 46.678c-2.02 1.312 47.902 7.313 47.902 7.313s9.133-43.979 9.235-44.989s-45.573-8-45.573-8");
}

.z_lw1mblg {
  fill: var(--svg-color--fff200, #fff200);
  d: path("m3.988 48.46l47.452 6.62L59.979 9L16.898 3.179z");
}

.zxn34rbad {
  fill: var(--svg-color--dbbf33, #dbbf33);
  d: path("m59.979 9l3.873 3.798l-8.166 48.905l-4.246-6.623z");
}

</style>
