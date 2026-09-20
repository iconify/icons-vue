<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1zsogt2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-trigger-right-sharp" /></template>
<style>
.u1zsogt2m {
  fill: currentColor;
  d: path("M3 19V8.27q0-1.357.977-2.323t2.35-.966h11.346q1.373 0 2.35.966T21 8.269V19zm4.158-3.846h.855V12.68H9.19l1.555 2.473h.99l-1.722-2.687q.622-.217.937-.645t.315-1.053q0-.938-.561-1.383q-.56-.444-1.724-.444H7.158zm.861-3.229L8 9.758h.933q.707 0 1.072.277q.364.278.364.784q0 .531-.357.819t-1.008.287zm6.443 3.229h.855V9.769h1.933v-.827h-4.734v.827h1.946z");
}

</style>
