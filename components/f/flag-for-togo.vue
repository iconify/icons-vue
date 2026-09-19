<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v9elqcbww"/><path class="oh0lr_bkw"/><path class="kl7plccip"/><path class="x4vzubcic"/><path class="ihaxtlb2q"/><path class="kfuohdc7x"/><path class="vuh9gnbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-togo" /></template>
<style>
.ihaxtlb2q {
  fill: var(--svg-color--009543, #009543);
  d: path("M10 54h44c5.881 0 9.193-3.881 9.865-9H.135c.672 5.119 3.984 9 9.865 9");
}

.kfuohdc7x {
  fill: var(--svg-color--c32129, #c32129);
  d: path("M10 10C4.119 10 .807 13.881.135 19A15 15 0 0 0 0 21v15h26V10z");
}

.kl7plccip {
  fill: var(--svg-color--009543, #009543);
  d: path("M26 28h38v8H26z");
}

.oh0lr_bkw {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M63.865 19H26v9h38v-7c0-.684-.049-1.351-.135-2");
}

.v9elqcbww {
  fill: var(--svg-color--009543, #009543);
  d: path("M63.865 19c-.672-5.119-3.984-9-9.865-9H26v9z");
}

.vuh9gnbjq {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("m21.574 20.393l-6.661.009l-2.066-6.738l-2.053 6.738l-6.666-.009l5.399 4.103l-2.093 6.694l5.42-4.16l5.424 4.16l-2.095-6.694z");
}

.x4vzubcic {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M0 36v7c0 .684.049 1.351.135 2h63.73c.086-.649.135-1.316.135-2v-7z");
}

</style>
