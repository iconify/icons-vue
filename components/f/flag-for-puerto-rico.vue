<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jj42t4fcb"/><path class="nc4avd7mq"/><path class="ovpt1zxpr"/><path class="gh_igeh4g"/><path class="fofb0z_lg"/><path class="v0kksz4jj"/><path class="ug650xbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-puerto-rico" /></template>
<style>
.fofb0z_lg {
  fill: var(--svg-color--ea0b19, #EA0B19);
  d: path("M1.371 30.01c.703.615 1.621.99 2.629.99h28a4 4 0 0 0 4-4v-1H6.923l-5.552 4.01z");
}

.gh_igeh4g {
  fill: var(--svg-color--eee, #EEE);
  d: path("M6.923 26H36v-5H13.846z");
}

.jj42t4fcb {
  fill: var(--svg-color--ea0b19, #EA0B19);
  d: path("M32 5H4a3.978 3.978 0 0 0-2.629.99L6.923 10H36V9a4 4 0 0 0-4-4z");
}

.nc4avd7mq {
  fill: var(--svg-color--eee, #EEE);
  d: path("M13.846 15H36v-5H6.923z");
}

.ovpt1zxpr {
  fill: var(--svg-color--ea0b19, #EA0B19);
  d: path("M18 18l-4.154 3H36v-6H13.846z");
}

.ug650xbxq {
  fill: var(--svg-color--fff, #FFF);
  d: path("M8.187 18.838l2.313-1.675H7.641l-.888-2.726l-.89 2.726H3l2.315 1.677l-.89 2.723l2.325-1.684l2.325 1.684z");
}

.v0kksz4jj {
  fill: var(--svg-color--0f55ec, #0F55EC);
  d: path("M13.846 21L18 18l-4.154-3l-6.923-5l-5.552-4.01A3.988 3.988 0 0 0 0 9v18c0 1.201.532 2.276 1.371 3.01L6.923 26l6.923-5z");
}

</style>
