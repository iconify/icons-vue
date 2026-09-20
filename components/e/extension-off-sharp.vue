<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnzmmpz8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:extension-off-sharp" /></template>
<style>
.jnzmmpz8c {
  fill: currentColor;
  d: path("M20 17.15L6.85 4h1.2q.175-1.275 1.15-2.137T11.5 1q1.3 0 2.275.863T14.95 4H20v5.35q.9.45 1.45 1.3T22 12.5q0 1.025-.55 1.875T20 15.65zM3 21v-5.8q1.2 0 2.1-.762T6 12.5q0-1.15-.9-1.9T3 9.8V4l17 17zm17.475 2.325l-19.8-19.8L2.1 2.1l19.8 19.8z");
}

</style>
