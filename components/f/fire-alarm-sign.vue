<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2kcxwb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-alarm-sign" /></template>
<style>
.w2kcxwb6x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25M12.53 5.97q4.22 4.219 4.22 7.78q0 1.968-1.391 3.359T12 18.5t-3.359-1.391T7.25 13.75q0-2.561 1.97-4.53q.105-.106.243-.163T9.75 9t.287.057t.243.163q.015.014.029.03q.257-1.56 1.02-3.085q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.109.055.195.141");
}

</style>
