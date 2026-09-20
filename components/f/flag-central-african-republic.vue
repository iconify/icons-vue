<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q9u86nb8w"/><path class="bvubfybsi"/><path class="jkkarl48q"/><path class="pma9l9kin"/><path class="k-gr_2btc"/><path class="lvacubcvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-central-african-republic" /></template>
<style>
.bvubfybsi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 11.5h36V18H0z");
}

.jkkarl48q {
  fill: var(--svg-color--289728, #289728);
  d: path("M0 18h36v6.5H0z");
}

.k-gr_2btc {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M15 5h6v26h-6z");
}

.lvacubcvn {
  fill: var(--svg-color--ffce00, #ffce00);
  d: path("m6.878 7.612l-.68-2.094l-.681 2.094H3.316l1.781 1.294L4.417 11l1.781-1.294L7.979 11l-.681-2.094L9.08 7.612z");
}

.pma9l9kin {
  fill: var(--svg-color--ffce00, #ffce00);
  d: path("M0 24.5V27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2.5z");
}

.q9u86nb8w {
  fill: var(--svg-color--003082, #003082);
  d: path("M32 5H4a4 4 0 0 0-4 4v2.5h36V9a4 4 0 0 0-4-4");
}

</style>
