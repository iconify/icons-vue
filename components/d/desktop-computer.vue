<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="taov9tbih"/><path class="vwt4q-o6l"/><path class="uu_h4ob9a"/><path class="m0i_ii2oy"/><path class="urvrd_b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:desktop-computer" /></template>
<style>
.m0i_ii2oy {
  fill: var(--svg-color--324449, #324449);
  d: path("M43.37 35.869v-8.547c0-.066-.149-.128-.331-.128H21.613c-.172 0-.331.062-.331.128v8.547c0 .038.045.068.085.087c0 0 .01 0 .01.008h.011c.053.02.14.036.225.036h21.426c.182 0 .331-.062.331-.131");
}

.taov9tbih {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M47.97 59.34c0 2.424-2.699 4.391-6.02 4.391H22.703c-3.324 0-6.02-1.967-6.02-4.391V4.383c0-2.422 2.699-4.387 6.02-4.387h19.246c3.324 0 6.02 1.965 6.02 4.387V59.34z");
}

.urvrd_b_f {
  fill: var(--svg-color--243438, #243438);
  d: path("M33.06 47.46v-3.242c0-.026-.017-.051-.039-.051h-2.503c-.021 0-.038.024-.038.051v3.242a.05.05 0 0 0 .011.03v.004q.01.011.026.01h2.503c.023 0 .04-.022.04-.044m12.02-35.68c0 .473-5.709.855-12.756.855s-12.756-.382-12.756-.855c0-.469 5.709-.851 12.756-.851s12.756.382 12.756.851");
}

.uu_h4ob9a {
  fill: var(--svg-color--243438, #243438);
  d: path("M33.811 56.622v-5.115c0-.04-.029-.08-.062-.08h-3.956c-.03 0-.062.04-.062.08v5.115c0 .019.009.038.015.051h.005q.016.023.042.024h3.956c.032 0 .062-.037.062-.075");
}

.vwt4q-o6l {
  fill: var(--svg-color--d1d2d3, #d1d2d3);
  d: path("M28.462 59.34V4.383c0-2.421 2.7-4.387 6.03-4.387H22.705c-3.324 0-6.02 1.965-6.02 4.387V59.34c0 2.424 2.7 4.391 6.02 4.391h11.787c-3.325-.001-6.03-1.967-6.03-4.391");
}

</style>
