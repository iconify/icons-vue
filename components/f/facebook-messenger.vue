<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlc07tbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:facebook-messenger" /></template>
<style>
.wlc07tbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.324 33.435C50.288 19.151 39.891 2.507 24 2.5C7.761 2.478-2.623 19.795 5.045 34.109l-.56 2.084l-1.928 7.202a1.673 1.673 0 0 0 2.049 2.048l7.2-1.928l2.074-.555c6.081 3.253 13.762 3.304 19.96.28m-13.315-26.2l6.668 6.667l9.776-6.667l-6.667 9.776l-2.825 4.146l-6.667-6.667l-9.777 6.667l6.668-9.776Zm22.799 16.395a21.29 21.259 0 0 1-9.483 9.806");
}

</style>
