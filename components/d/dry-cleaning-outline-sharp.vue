<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ggmtt3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dry-cleaning-outline-sharp" /></template>
<style>
.x5ggmtt3w {
  fill: currentColor;
  d: path("M7.75 21v-5.673H4v-3.058l7.5-3.338V7.685q-.823-.171-1.354-.819q-.53-.647-.53-1.481q0-.994.692-1.69Q11.001 3 11.991 3t1.682.702t.693 1.683h-1.039q0-.589-.381-.987Q12.564 4 12 4q-.588 0-.986.398t-.398.987t.398.986t.986.398h.5v2.162l7.5 3.358v3.038h-3.75V21zM5 14.327h2.75v-.942h8.5v.942H19v-1.392l-7-3.12l-7 3.12zM8.75 20h6.5v-5.615h-6.5zm0-5.616h6.5z");
}

</style>
