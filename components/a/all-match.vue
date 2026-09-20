<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6baw4a2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:all-match" /></template>
<style>
.p6baw4a2k {
  fill: currentColor;
  d: path("m3 19l5.5-7L3 4.98h11.673q.379 0 .718.156q.338.155.555.453L21 12l-.183.214q-.663-.326-1.369-.491T18 11.558q-2.733 0-4.645 1.912t-1.913 4.64q0 .211.017.445q.018.233.072.445zm12.04 2.076q-1.213-1.213-1.213-2.96q0-1.749 1.213-2.961T18 13.942t2.96 1.213t1.213 2.96q0 1.749-1.213 2.961T18 22.288t-2.96-1.212m2.331-1.249l2.84-2.796l-.626-.627l-2.214 2.183l-.955-.975l-.627.632z");
}

</style>
