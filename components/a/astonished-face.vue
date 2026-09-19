<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lx7_3y9vq"/><path class="zww2e28oa"/><path class="xtd61ac7a"/><g class="wj59n8bve"><path class="m0jmylgbd"/><path class="hf_mmf_mw"/><path class="x8jwd0b2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:astonished-face" /></template>
<style>
.hf_mmf_mw {
  d: path("M14.521 20.19a1.89 1.89 0 1 0-2.673 2.677l12.208 12.21a1.89 1.89 0 0 0 2.677-.002a1.89 1.89 0 0 0 0-2.673zm24.304 14.89a1.89 1.89 0 1 1-2.675-2.675l12.209-12.213a1.89 1.89 0 0 1 2.675.002a1.89 1.89 0 0 1 0 2.675z");
}

.lx7_3y9vq {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.79 31.895c0 17.619-14.276 31.895-31.895 31.895C14.277 63.79 0 49.514 0 31.895C0 14.279 14.277 0 31.895 0S63.79 14.279 63.79 31.895");
}

.m0jmylgbd {
  d: path("M14.521 35.08a1.89 1.89 0 0 1-2.673-2.675l12.208-12.213a1.893 1.893 0 0 1 2.677 2.677z");
}

.wj59n8bve {
  fill: var(--svg-color--633d19, #633d19);
}

.x8jwd0b2i {
  d: path("M38.825 20.19a1.893 1.893 0 0 0-2.675 2.677l12.209 12.21a1.89 1.89 0 0 0 2.675-.002c.74-.738.74-1.936 0-2.673zM24.654 6.895c-5.935-.41-11.317 2.023-15.04 6.642c-1.617 2 1.219 4.877 2.852 2.852c3.126-3.876 7.196-5.807 12.189-5.46c2.599.179 2.582-3.857 0-4.03m15.267-.004c5.934-.41 11.315 2.023 15.04 6.642c1.615 2-1.222 4.877-2.853 2.852c-3.128-3.876-7.197-5.807-12.189-5.46c-2.6.179-2.58-3.857 0-4.03");
}

.xtd61ac7a {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.18 51.52c-1.088-3.701-4.553-7.306-7.283-7.306s-6.197 3.604-7.282 7.306z");
}

.zww2e28oa {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M40.98 54.16c0 5.147-4.882 7.07-8.782 7.07c-3.904 0-9.39-1.92-9.39-7.07c0-5.146 5.183-11.336 9.09-11.336s9.09 6.191 9.09 11.336");
}

</style>
