<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rl1cpz9vl"/><path class="f_xx2xjft"/><path class="tkdfkgv2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:keycap-4" /></template>
<style>
.f_xx2xjft {
  fill: var(--svg-color--fff, #fff);
  d: path("M57 45.7c0 4.6-3.7 8.3-8.3 8.3H15.3C10.7 54 7 50.3 7 45.7V12.3C7 7.7 10.7 4 15.3 4h33.3c4.6 0 8.3 3.7 8.3 8.3v33.4z");
}

.rl1cpz9vl {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

.tkdfkgv2l {
  fill: var(--svg-color--9aa0a5, #9aa0a5);
  d: path("M33.7 45v-6.4H20v-5.3L34.5 13h5.4v20.2H44v5.4h-4.1V45zm0-11.8V22.3L26 33.2z");
}

</style>
