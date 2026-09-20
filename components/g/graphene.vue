<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":302};
const content = `<path class="qyiqp_y3y"/><path class="gu9cak9yf"/><path class="ln1ughbef"/><path class="b7qbmqb7k"/><path class="la8miyb5i"/><path class="qhvktkwgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:graphene" /></template>
<style>
.b7qbmqb7k {
  fill: var(--svg-color--eb1919, #eb1919);
  d: path("m0 74.98l22.312 13.161V213.21l106.344 62.293v26.412L0 225.554zm211.928 26.845v98.372l22.338 12.636V106.582z");
}

.gu9cak9yf {
  fill: var(--svg-color--f25f3f, #f25f3f);
  d: path("M150.245 12.728v26.034L44.11 101.237v99.38l-21.921 12.639V88.333z");
}

.la8miyb5i {
  fill: var(--svg-color--f25f3f, #f25f3f);
  d: path("M127.928 301.933v-26.034l106.134-63.074v-98.406l-106.134 62.57v-25.915l128.055-75.676v150.93z");
}

.ln1ughbef {
  fill: var(--svg-color--ffaa5b, #ffaa5b);
  d: path("M149.919 12.893L127.888 0L.226 74.961L22.259 88.58zm104.888 187.499l-21.79-12.71l-105.628 61.062l-83.175-48.352l-22.105 12.918l83.247 49.333l22.033 13.619zm1.196-124.932l-22.604-12.514l-127.661 74.962l22.033 13.618z");
}

.qhvktkwgx {
  fill: var(--svg-color--eb1919, #eb1919);
  d: path("M106.191 137.695v26.145l21.851 13.01v-25.883z");
}

.qyiqp_y3y {
  fill: var(--svg-color--f25f3f, #f25f3f);
  d: path("m127.888 0l22.031 12.893l-11.474 6.801l11.8-6.966v26.034L44.11 101.237v99.216l.104-.061l83.175 48.352l84.539-48.872v-72.405l-84.001 49.523l-.001-.209l-21.735-12.941l-.001-25.653l-.452-.279l127.661-74.962l22.539 12.478l.044-.026v.051l.021.011l-.021.012v150.856l-127.327 75.175l.001.412l-.348-.207l-.381.225l-.001-.452L0 225.554V74.98l5.623 3.317l-5.397-3.336z");
}

</style>
