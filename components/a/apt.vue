<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeI32dd2V)" class="ohm5fxx1o"/><defs><linearGradient id="SVGeI32dd2V" x1="19.223" x2="9.84" y1="20.899" y2="4.315" gradientUnits="userSpaceOnUse"><stop offset=".11" class="sxbkb1bax"/><stop offset=".18" class="m5_197hjz"/><stop offset=".33" class="uhfh96vkv"/><stop offset=".53" class="zbk47lqvs"/><stop offset=".81" class="v-4uj_b9h"/><stop offset=".97" class="mkujud60v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apt" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m5_197hjz {
  stop-color: var(--svg-color--ba6bff, #ba6bff);
}

.mkujud60v {
  stop-color: var(--svg-color--3fc, #3fc);
}

.ohm5fxx1o {
  d: path("M17.158 9.625L6.83 13.293a.767.767 0 0 1-1.018-.855l.956-5.198a.75.75 0 0 1 .27-.455l4.478-3.612a.77.77 0 0 1 .973 0l4.5 3.628c.13.107.226.248.265.405l.394 1.502a.77.77 0 0 1-.49.917m-11.937 6.24l-.517 2.632a.755.755 0 0 0 .399.827A15.2 15.2 0 0 0 12.006 21a15.1 15.1 0 0 0 6.834-1.643a.856.856 0 0 0 .456-.928l-1.238-6.582a.77.77 0 0 0-1.023-.579L5.727 15.29a.77.77 0 0 0-.506.574");
}

.sxbkb1bax {
  stop-color: var(--svg-color--c65cff, #c65cff);
}

.uhfh96vkv {
  stop-color: var(--svg-color--9991ff, #9991ff);
}

.v-4uj_b9h {
  stop-color: var(--svg-color--42f0db, #42f0db);
}

.zbk47lqvs {
  stop-color: var(--svg-color--6cf, #6cf);
}

</style>
