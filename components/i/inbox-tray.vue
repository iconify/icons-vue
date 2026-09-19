<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nxvp979uw"/><path class="nt31-o_uh"/><path class="khpjc8-nz"/><path class="bxo09ebpl"/><path class="yvme9ebwu"/><path class="arsyp_b0l"/><path class="j6em_is4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:inbox-tray" /></template>
<style>
.arsyp_b0l {
  fill: var(--svg-color--5b7f38, #5b7f38);
  d: path("m48.5 34l-5.6-2.2s2.7-10.2-4.6-20.1C31.5 2.5 23 0 23 0l-1.4.3s7.3 5.3 9.4 14.4c1.3 5.5.6 10.6.2 12.3l-4.8-1.9h-2.1L30 46.8h2.1z");
}

.bxo09ebpl {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M35.4 47.5s-.3 7-1.7 8.3c-2.7 2.6-11.1 2.6-13.9 0c-1.4-1.3-1.7-8.3-1.7-8.3H0V64h53.5V47.5z");
}

.j6em_is4i {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M21.5.3s5 4.8 8 13.7c2.5 7.3.5 13.3.5 13.3l-5.8-2.2L30 46.8L46.4 34l-5.6-2.2s2.7-10.2-4.6-20.1C29.3 2.5 21.5.3 21.5.3");
}

.khpjc8-nz {
  fill: var(--svg-color--f2bc97, #f2bc97);
  d: path("M24.9 51.4L0 64h53.5L64 51.4z");
}

.nt31-o_uh {
  fill: var(--svg-color--b77e58, #b77e58);
  d: path("M24.9 39H64v12.3H24.9z");
}

.nxvp979uw {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M24.9 39v12.4L0 64V47.5z");
}

.yvme9ebwu {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M64 51.4L53.5 64V47.5L64 39z");
}

</style>
