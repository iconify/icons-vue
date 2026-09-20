<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2u3kct8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-info-sharp" /></template>
<style>
.j2u3kct8e {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v6.125q-1-1.05-2.3-1.588T16.975 10q-2.9 0-4.937 2.038T10 16.975q0 .8.175 1.55T10.7 20zm11.463.538Q12 19.075 12 17t1.463-3.537T17 12t3.538 1.463T22 17t-1.463 3.538T17 22t-3.537-1.463M16.5 20h1v-4h-1zm.85-5.15q.15-.15.15-.35t-.15-.35T17 14t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
