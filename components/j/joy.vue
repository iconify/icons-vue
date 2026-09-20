<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vi36y5bho"/><path class="wo3hnfbwz"/><path class="p3g0ec6zs"/><path class="n0851n-wb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:joy" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n0851n-wb {
  fill: var(--svg-color--faeadd, #faeadd);
  d: path("M14.292 4.65a3 3 0 0 0-1.597-.546c-.276.018-.822.157-.822.546c0 .492.48.972.78 1.236c.294.265 1.002.738 1.782.738s.864-.467.864-.6s-.083-.78-1.008-1.374");
}

.p3g0ec6zs {
  fill: var(--svg-color--e85754, #e85754);
  d: path("M12 11.7a4.2 4.2 0 1 0 0-8.4a4.2 4.2 0 0 0 0 8.4");
}

.vi36y5bho {
  fill: var(--svg-color--fffffd, #fffffd);
  d: path("M3 18.186V20.7h18v-2.514c0-.6-.468-1.086-1.044-1.086H4.044C3.468 17.1 3 17.586 3 18.186m7.6-7.486h2.8v5.6h-2.8z");
}

.wo3hnfbwz {
  fill: var(--svg-color--ebc5fe, #ebc5fe);
  d: path("M7.8 15.769V17.1h8.4v-1.332a.48.48 0 0 0-.486-.468H8.28a.48.48 0 0 0-.486.468z");
}

</style>
