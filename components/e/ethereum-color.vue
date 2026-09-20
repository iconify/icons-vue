<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":427};
const content = `<path class="b354z4bad"/><path class="scz4a7b-l"/><path class="a9d_w-dci"/><path class="pe774hs8f"/><path class="so5w_5bgx"/><path class="w5i4i4gzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ethereum-color" /></template>
<style>
.a9d_w-dci {
  fill: var(--svg-color--d995d1, #d995d1);
  d: path("m144.238 156.998l84.775 47.215l3.005 9.187l-10.094 8.812l-77.686-43.358z");
}

.b354z4bad {
  fill: var(--svg-color--5a9ded, #5a9ded);
  d: path("M256 241.65L128 426.8V322.457zm-67.84 65.08l-41.09 25.858v33.473z");
}

.pe774hs8f {
  fill: var(--svg-color--a6e276, #a6e276);
  d: path("m111.818 156.998l-84.775 47.215l-3.005 9.187l10.094 8.812l77.686-43.358z");
}

.scz4a7b-l {
  fill: var(--svg-color--53d3e0, #53d3e0);
  d: path("M0 241.65L128 426.8V322.457zm67.84 65.08l41.09 25.858v33.473z");
}

.so5w_5bgx {
  fill: var(--svg-color--ff9c92, #ff9c92);
  d: path("m128 0l128 219.203l-128 80.608zm18.904 70.317V266.03l83.622-52.631z");
}

.w5i4i4gzi {
  fill: var(--svg-color--ffe94d, #ffe94d);
  d: path("M128 0L0 219.203l128 80.608zm-18.904 70.317V266.03L25.474 213.4z");
}

</style>
