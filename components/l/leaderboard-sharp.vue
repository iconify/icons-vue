<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lki_8vbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:leaderboard-sharp" /></template>
<style>
.lki_8vbci {
  fill: currentColor;
  d: path("M2 21V9h5.5v12zm7.25 0V3h5.5v18zm7.25 0V11H22v10z");
}

</style>
