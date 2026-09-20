<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="osi6c3bvt"/><ellipse class="nzxpe1b1v"/><circle class="cwnrgib_c"/><path class="h1c3czzkn"/><path class="krj0oyb6t"/><path class="v3fv_nz3c"/><path class="ex0o_6hwc"/><path class="a1fnu1bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-monocle" /></template>
<style>
.a1fnu1bws {
  fill: var(--svg-color--bdddf4, #bdddf4);
  d: path("M28.049 9.411a5.8 5.8 0 0 0-3.167-.94a5.824 5.824 0 0 0-5.824 5.824c0 1.169.348 2.255.94 3.167zm-5.652 10.144a5.8 5.8 0 0 0 2.485.563a5.824 5.824 0 0 0 5.824-5.824c0-.89-.206-1.731-.563-2.485z");
}

.cwnrgib_c {
  cx: 24.882px;
  cy: 14.294px;
  r: 6.882px;
  fill: var(--svg-color--f4f7f9, #f4f7f9);
}

.ex0o_6hwc {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M21.175 28.588c-.159 0-.321-.036-.473-.112c-1.819-.91-3.587-.91-5.406 0a1.059 1.059 0 1 1-.947-1.895c2.421-1.21 4.877-1.21 7.3 0a1.06 1.06 0 0 1-.474 2.007");
}

.h1c3czzkn {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M14.825 9.946c-.322 0-.64-.146-.848-.423c-.991-1.321-2.028-2.029-3.083-2.104c-1.39-.095-2.523.947-2.734 1.158A1.057 1.057 0 1 1 6.663 7.08c.457-.457 2.129-1.936 4.381-1.773c1.695.12 3.251 1.111 4.627 2.945a1.059 1.059 0 0 1-.846 1.694");
}

.krj0oyb6t {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M32.824 36a1.06 1.06 0 0 1-1.059-1.059V14.824a1.059 1.059 0 1 1 2.118 0v20.118A1.06 1.06 0 0 1 32.824 36");
}

.nzxpe1b1v {
  cx: 12.176px;
  cy: 14.71px;
  fill: var(--svg-color--65471b, #65471b);
  rx: 2.647px;
  ry: 3.706px;
}

.osi6c3bvt {
  fill: var(--svg-color--ffcb4c, #ffcb4c);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.v3fv_nz3c {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M32.824 12.706c-.054 0-.105.012-.158.016c-.732-3.628-3.943-6.369-7.784-6.369c-4.379 0-7.941 3.562-7.941 7.941s3.562 7.941 7.941 7.941c3.468 0 6.416-2.238 7.496-5.343q.216.048.445.049a2.118 2.118 0 0 0 .001-4.235m-7.942 7.412c-3.211 0-5.823-2.612-5.823-5.824s2.613-5.824 5.823-5.824s5.824 2.612 5.824 5.824s-2.613 5.824-5.824 5.824");
}

</style>
