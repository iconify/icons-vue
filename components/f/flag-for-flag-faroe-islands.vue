<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nhj24fqoo"/><path class="jzgdlgbbh"/><path class="k74_wxarn"/><path class="dqdjaob6t"/><path class="pnr-hgb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-faroe-islands" /></template>
<style>
.dqdjaob6t {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M15 16V5h-4v11H0v4h11v11h4V20h21v-4z");
}

.jzgdlgbbh {
  fill: var(--svg-color--0065bd, #0065bd);
  d: path("M36 16v-1.5H16.5V5H15v11zM11 5H9.444v9.5H0V16h11z");
}

.k74_wxarn {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 21.5V27a4 4 0 0 0 4 4h5.444v-9.5zm16.5 0V31H32a4 4 0 0 0 4-4v-5.5z");
}

.nhj24fqoo {
  fill: var(--svg-color--eee, #eee);
  d: path("M9.444 5H4a4 4 0 0 0-4 4v5.5h9.444zM36 14.5V9a4 4 0 0 0-4-4H16.5v9.5z");
}

.pnr-hgb6j {
  fill: var(--svg-color--0065bd, #0065bd);
  d: path("M15 20v11h1.5v-9.5H36V20zm-4 0H0v1.5h9.444V31H11z");
}

</style>
