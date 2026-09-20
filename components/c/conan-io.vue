<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":241,"height":256};
const content = `<path class="sb0r_dbgu"/><path class="q4-_4ebtc"/><path class="k1sd-ivzk"/><path class="pz5he6b_k"/><path class="vhwpggsux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:conan-io" /></template>
<style>
.k1sd-ivzk {
  fill: var(--svg-color--7da7d3, #7da7d3);
  d: path("M118.874 129.541V256l121.404-79.019V63.449z");
}

.pz5he6b_k {
  fill: var(--svg-color--369, #369);
  d: path("m184.556 213.249l2.831-1.843l-2.4-117.857l-2.143 1.166z");
}

.q4-_4ebtc {
  fill: var(--svg-color--69c, #69c);
  d: path("M0 170.587L118.874 256V129.541L0 56.985z");
}

.sb0r_dbgu {
  fill: var(--svg-color--afd4e5, #afd4e5);
  d: path("M118.874 0L0 56.984l118.874 72.557l121.404-66.093z");
}

.vhwpggsux {
  fill: var(--svg-color--69c, #69c);
  d: path("m161.91 77.054l30.502-16.468s-45.97-50.157-100.11-21.033C66.83 53.255 59.24 67.026 70.516 81.73c18.662 24.338 41.17 21.606 41.17 21.606L141.04 89.05s-31.876 4.205-45.356-6.959c-11.057-9.159-6.414-20.817 8.845-31.44c13.388-9.321 40.036-5.565 49.479 1.564c9.442 7.127 13.11 17.095 7.903 24.839");
}

</style>
