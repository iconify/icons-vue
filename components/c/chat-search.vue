<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha89ucb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-search" /></template>
<style>
.ha89ucb2d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v8q0 3.25-3.25 3.25h-6.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zm4.5 3.25q0 1.45 1.025 2.476q1.025 1.025 2.475 1.025q1.06 0 1.893-.548l1.327 1.327q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-1.327-1.327q.548-.834.547-1.893q.001-1.45-1.025-2.476Q12.7 5.749 11.25 5.749T8.775 6.774T7.75 9.25");
}

</style>
