<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rsz0kbczt"/><path class="lyoabd47f"/><path class="t42tkekqp"/><path class="vpvs36pfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-gambia" /></template>
<style>
.lyoabd47f {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 24h64v3H0zm0 13h64v3H0z");
}

.rsz0kbczt {
  fill: var(--svg-color--002664, #002664);
  d: path("M0 25h64v14H0z");
}

.t42tkekqp {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v3h64v-3c0-6.075-3.373-11-10-11");
}

.vpvs36pfv {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-3H0z");
}

</style>
