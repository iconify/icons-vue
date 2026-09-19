<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f5tajnb5c"/><path class="mu9jqtixv"/><path class="f3md7bwsa"/><path class="hk1dtpsip"/><path class="dfw5whbzk"/><path class="vbm5bjbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:file-folder" /></template>
<style>
.dfw5whbzk {
  fill: var(--svg-color--d9e3e8, #d9e3e8);
  d: path("m57.1 29.7l4.2-27.3l-54.4 23l4.3 38.1z");
}

.f3md7bwsa {
  fill: var(--svg-color--b3c0c4, #b3c0c4);
  d: path("M54.9 27.8L58.8.9L4.7 22.1l6.5 41.4z");
}

.f5tajnb5c {
  fill: var(--svg-color--962c2c, #962c2c);
  d: path("M54.4.2L29.8 8.7s-.9-2-1.7-3.1c-1.9-2.8-5.2-1.9-5.2-1.9L4.1 9.8s-2.6 1.1-3.6 4c-1 2.8 0 6.3 0 6.3l10.8 44l43.1-37.6S55.8 9.7 56.7 2C57-.8 54.4.2 54.4.2");
}

.hk1dtpsip {
  fill: var(--svg-color--c5cfd3, #c5cfd3);
  d: path("m55.9 28.6l4.4-27.2L5.8 23.6l5.4 39.9z");
}

.mu9jqtixv {
  fill: var(--svg-color--9aabaf, #9aabaf);
  d: path("M53.6 24.9L57.5.2L3.4 20.5l7.8 43z");
}

.vbm5bjbbq {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("m11.3 64l47.1-33.4L64 5.8s.3-.8-.5-1.8c-.6-.7-1.5-.4-1.5-.4L36.7 14.3s-1.5 6-4.5 7.6c-3.3 1.7-18.8 9.3-18.8 9.3s-2.2 1.3-3.5 3.4c-1.2 2-1.4 4.5-1.4 4.5z");
}

</style>
