<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd16pbbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bus-railway" /></template>
<style>
.cd16pbbmk {
  fill: currentColor;
  d: path("M9.293 15.293q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M13.577 21l1.692-1.692q-.69 0-1.191-.501t-.501-1.192v-3q0-1.506 1.048-2.445q1.048-.94 2.683-.94t2.663.94T21 14.616v3q0 .69-.501 1.19t-1.191.502L21 21zm4.092-3.35q.197-.196.197-.477t-.197-.477t-.477-.196t-.476.196q-.197.196-.197.477t.197.477t.476.196t.477-.196m-3.207-2.189h5.654v-.846q0-.236-.041-.438q-.04-.202-.121-.408h-5.331q-.08.206-.121.408t-.04.439zM7.039 20q-.214 0-.357-.143t-.143-.357v-1.896q-.489-.212-1.014-.901T5 15.115V6q0-1.556 1.685-2.278Q8.369 3 12 3q3.762 0 5.38.694T19 6v3.054q-.238-.073-.479-.113q-.24-.039-.521-.07V6.538H6V11h6.423q-.615.767-.923 1.696t-.308 1.92V18H7.77v1.5q0 .214-.143.357T7.269 20z");
}

</style>
