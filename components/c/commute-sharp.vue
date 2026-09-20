<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl7dzgb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:commute-sharp" /></template>
<style>
.rl7dzgb_o {
  fill: currentColor;
  d: path("M11.673 18.039v1.692h-1v-5.966l1.452-4.15h7.866l1.451 4.15v5.966h-1v-1.693zm.23-5.078h8.309l-.854-2.461h-6.6zm1.232 3.347q.367 0 .626-.259q.258-.258.258-.626q0-.367-.258-.626q-.259-.258-.626-.258q-.368 0-.626.258q-.259.259-.259.626q0 .368.259.626q.258.259.625.259m5.847 0q.367 0 .626-.259q.259-.258.259-.626q0-.367-.26-.626q-.258-.258-.625-.258t-.626.258q-.259.259-.259.626q0 .368.259.626q.258.259.626.259M4.558 19.5v-.308L6.25 17.5q-1.404 0-2.548-.615Q2.558 16.269 2.558 15V6.5q0-1.016 1.494-1.508T8.558 4.5q3.046 0 4.523.487T14.558 6.5v1.346h-1V6.5h-10v7h5.346v6zm1.126-3.874q.258-.259.258-.626t-.258-.626t-.626-.258t-.626.258q-.259.259-.259.626t.259.626t.626.259t.626-.259");
}

</style>
