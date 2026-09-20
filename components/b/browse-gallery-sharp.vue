<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaw_ahydw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browse-gallery-sharp" /></template>
<style>
.jaw_ahydw {
  fill: currentColor;
  d: path("m11.8 15.489l.689-.689L9.5 11.812V7.5h-1v4.689zm6.2 3.934V18.3q1.85-.875 2.925-2.575T22 12t-1.075-3.725T18 5.7V4.577q2.264.95 3.632 2.96T23 12t-1.368 4.463T18 19.423m-12.118-.049q-1.455-.626-2.543-1.713t-1.713-2.543T1 12t.626-3.118T3.34 6.34t2.542-1.714T9 4t3.118.626T14.66 6.34t1.714 2.542T17 12t-.626 3.118t-1.714 2.542t-2.542 1.714T9 20t-3.118-.626");
}

</style>
