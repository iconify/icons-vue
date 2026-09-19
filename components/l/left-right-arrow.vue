<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jpj71oejp"/><g class="n1mjunbsu"><path class="orahjbcou"/><path class="b01poqbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:left-right-arrow" /></template>
<style>
.b01poqbal {
  d: path("m44.41 18.843l15.14 13.162l-15.13 13.07c-2.112-.169-3.762-1.582-3.762-3.304v-2.924H26.94a4.18 4.18 0 0 1-4.182-4.178v-5.422a4.183 4.183 0 0 1 4.182-4.182h13.718v-2.921c0-1.719 1.646-3.133 3.754-3.302");
}

.jpj71oejp {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.918 57.025a6.89 6.89 0 0 1-6.891 6.895H6.888A6.89 6.89 0 0 1 0 57.025V6.891A6.89 6.89 0 0 1 6.888 0h50.139a6.89 6.89 0 0 1 6.891 6.891z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.orahjbcou {
  d: path("M19.502 18.843L4.362 32.005l15.13 13.07c2.11-.169 3.762-1.582 3.762-3.304v-2.924h13.719a4.18 4.18 0 0 0 4.182-4.178v-5.422a4.183 4.183 0 0 0-4.182-4.182H23.254v-2.921c0-1.719-1.645-3.133-3.754-3.302");
}

</style>
