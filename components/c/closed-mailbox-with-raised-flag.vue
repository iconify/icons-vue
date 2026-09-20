<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rxzk324rt"/><path class="k3ruj4gdt"/><path class="ax5-6d64w"/><path class="chv16ab2k"/><path class="zvqc9nbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:closed-mailbox-with-raised-flag" /></template>
<style>
.ax5-6d64w {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M10 3a8 8 0 0 0-8 8v12h16V11a8 8 0 0 0-8-8");
}

.chv16ab2k {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M9 3c-3.866 0-7 3.582-7 8v12h14V11c0-4.418-3.134-8-7-8");
}

.k3ruj4gdt {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M26 3H10v20h24V11a8 8 0 0 0-8-8");
}

.rxzk324rt {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M22 33c0 2.209-8 2.209-8 0V23a4 4 0 0 1 8 0z");
}

.zvqc9nbed {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M26 1h-4a2 2 0 0 0-2 2v12a2 2 0 0 0 4 0V7h2a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2");
}

</style>
