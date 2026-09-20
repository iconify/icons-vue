<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gfldstbfu"/><path class="olcfhvxka"/><path class="tnsvawbdw"/><path class="x_r1_q5wc"/><path class="n4xwhzbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-panama" /></template>
<style>
.gfldstbfu {
  fill: var(--svg-color--eee, #eee);
  d: path("M18 18V5H4a4 4 0 0 0-4 4v9zm0 0v13h14a4 4 0 0 0 4-4v-9z");
}

.n4xwhzbkv {
  fill: var(--svg-color--d21034, #d21034);
  d: path("m25.91 24.854l-.673 2.073L27 25.646l1.763 1.281l-.673-2.073l1.763-1.281h-2.179L27 21.5l-.674 2.073h-2.179z");
}

.olcfhvxka {
  fill: var(--svg-color--005293, #005293);
  d: path("M18 18v13H4a4 4 0 0 1-4-4v-9z");
}

.tnsvawbdw {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M18 18V5h14a4 4 0 0 1 4 4v9z");
}

.x_r1_q5wc {
  fill: var(--svg-color--005293, #005293);
  d: path("M9.674 10.573L9 8.5l-.674 2.073H6.147l1.763 1.281l-.673 2.073L9 12.646l1.763 1.281l-.673-2.073l1.763-1.281z");
}

</style>
