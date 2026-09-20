<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmvqiibgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-recirculate-2-rounded" /></template>
<style>
.xmvqiibgd {
  fill: currentColor;
  d: path("M14.116 10.529q0-1.008-.723-1.71q-.722-.703-1.749-.703H8.173q-.171 0-.297.116t-.126.307q0 .17.126.306t.297.136h3.471q.652 0 1.12.458t.467 1.09t-.467 1.08t-1.12.449H9.048l.63-.612q.13-.129.13-.304t-.13-.303q-.128-.13-.303-.13t-.304.13L7.97 11.916q-.242.242-.242.577t.242.578l1.102 1.077q.129.129.304.12t.304-.14q.129-.147.129-.312q0-.166-.148-.295l-.612-.598h2.596q1.008 0 1.74-.703t.732-1.691M6.75 19q-.89 0-1.606-.518q-.715-.518-1.121-1.328H1.808q-.348 0-.578-.23T1 16.346v-4.134q0-.69.463-1.153t1.152-.463h1.116l1.538-4.155q.167-.427.545-.684T6.65 5.5h7.123q.39 0 .718.195t.546.51l2.424 3.91l3.964.312q.69.056 1.133.539q.442.482.442 1.173v4.207q0 .348-.23.578t-.578.23h-2.234q-.387.81-1.102 1.328T17.25 19t-1.606-.518t-1.121-1.328H9.458q-.387.81-1.102 1.328T6.75 19");
}

</style>
