<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b462j_b_t"/><path class="khc8tvbau"/><path class="t3yzrobvx"/><path class="biz-lzboy"/><path class="g7vzs_bcg"/><path class="g9sbvrb3f"/><path class="db0prcurn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ice-cream" /></template>
<style>
.b462j_b_t {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M20 28.625S30.661 25.9 33.356 15.72c.396-1.495-1.518-2.72-3.868-2.72H5.999c-1.175 0-3.74.493-3.072 2.894C5.711 25.9 16 28.625 16 28.625v1.173s-4.634 2.443-5.588 3.01c-1.027.588-.268 1.526.144 1.689c.684.269 2.39 1.15 7.116 1.15c4.847 0 7.497-.954 8.083-1.15c.226-.075 1.197-.973-.198-1.799c-2.484-1.47-5.557-2.9-5.557-2.9z");
}

.biz-lzboy {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M33.291 14.217c0 1.613-3.132 4.223-7.83 4.223c-4.326 0-7.832 1.393-7.832-4.223a7.831 7.831 0 0 1 15.662 0");
}

.db0prcurn {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M2.837 15.177c1.396.6 15.488 5.046 30.498.087c0 .652-.411 2.477-.653 3.175c-.391 1.132-15.401 4.83-28.888.261c-.392-.173-1.566-3.784-.957-3.523");
}

.g7vzs_bcg {
  fill: var(--svg-color--8a4b38, #8a4b38);
  d: path("M18.672 14.217c0 5.182-3.132 4.311-7.831 4.311c-4.325 0-7.831-1.653-7.831-4.311a7.83 7.83 0 1 1 15.662 0");
}

.g9sbvrb3f {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M30.837 21.098a16.5 16.5 0 0 0 2.082-3.995c-13.485 4.732-26.07 1.375-29.477.336a16.8 16.8 0 0 0 1.797 3.446c11.35 3.251 21.551 1.204 25.598.213");
}

.khc8tvbau {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M33.291 15.248c0 1.692-6.835 3.064-15.269 3.064c-8.432 0-15.268-1.371-15.268-3.064s6.836-3.064 15.268-3.064c8.434 0 15.269 1.371 15.269 3.064");
}

.t3yzrobvx {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M25.982 6.908c0 1.613-3.133 4.745-7.832 4.745c-4.325 0-7.831-2.088-7.831-4.745c0-4.325 3.505-6.787 7.831-6.787c4.327.001 7.832 2.462 7.832 6.787");
}

</style>
