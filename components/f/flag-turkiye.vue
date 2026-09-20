<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="er7ll9b5k"/><path class="gcjct13tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-turkiye" /></template>
<style>
.er7ll9b5k {
  fill: var(--svg-color--e30917, #e30917);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.gcjct13tn {
  fill: var(--svg-color--eee, #eee);
  d: path("M16 24a6 6 0 1 1 0-12c1.31 0 2.52.425 3.507 1.138A7.33 7.33 0 0 0 14 10.647A7.353 7.353 0 0 0 6.647 18A7.353 7.353 0 0 0 14 25.354c2.195 0 4.16-.967 5.507-2.492A5.96 5.96 0 0 1 16 24m3.913-5.77l2.44.562l.22 2.493l1.288-2.146l2.44.561l-1.644-1.888l1.287-2.147l-2.303.98l-1.644-1.889l.22 2.494z");
}

</style>
