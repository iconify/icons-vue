<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kyd_ykbbs"/><path class="zv48vub2b"/><path class="rrjvpbcwu"/><path class="pj0um5x8d"/><path class="kzy028b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bookmark-tabs" /></template>
<style>
.kyd_ykbbs {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("m30.415 9.586l-9-9a2.001 2.001 0 0 0-2.829 2.829l-3.859 3.859l9 9l3.859-3.859a2 2 0 0 0 2.829-2.829");
}

.kzy028b5t {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M33 19s-8.056-.002-8.084 0c-.291 0-.91.139-1.255.485l-2.328 2.342a1.665 1.665 0 0 0 0 2.344l2.328 2.342c.345.346.964.487 1.255.487c.028.002 8.084 0 8.084 0c1.104 0 2-.897 2-2.001V21a2 2 0 0 0-2-2");
}

.pj0um5x8d {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M31 19s-5.906-.002-5.935 0c-.291 0-.91.174-1.255.606l-2.328 2.929c-.644.809-.644 2.119 0 2.93l2.328 2.929c.345.432.964.606 1.255.606c.019.002 3.547 0 5.935 0z");
}

.rrjvpbcwu {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M20 0h-2v9a4 4 0 0 0 4 4h9v-2h-9c-1 0-2-1-2-2zm-5 8a1 1 0 0 1-1 1H6a1 1 0 0 1 0-2h8a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H6a1 1 0 0 1 0-2h8a1 1 0 0 1 1 1m12 4a1 1 0 0 1-1 1H6a1 1 0 0 1 0-2h20a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H6a1 1 0 1 1 0-2h20a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H6a1 1 0 1 1 0-2h20a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H6a1 1 0 1 1 0-2h20a1 1 0 0 1 1 1");
}

.zv48vub2b {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M20 0H5a4 4 0 0 0-4 4v28a4 4 0 0 0 4 4h22a4 4 0 0 0 4-4V11h-9c-1 0-2-1-2-2z");
}

</style>
