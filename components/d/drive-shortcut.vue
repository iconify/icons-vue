<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f30axccxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-shortcut" /></template>
<style>
.f30axccxk {
  fill: currentColor;
  d: path("M16 22q-3.425-.7-5.712-3.425Q8 15.85 8 12.2q0-2.575 1.175-4.713Q10.35 5.35 12.3 4H8V2h8v8h-2V5.3q-1.8 1.05-2.9 2.862Q10 9.975 10 12.2q0 2.8 1.7 4.937q1.7 2.138 4.3 2.813Z");
}

</style>
