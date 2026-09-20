<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw3mmsbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dual-screen-sharp" /></template>
<style>
.qw3mmsbzw {
  fill: currentColor;
  d: path("M4 18.95V2l10 4.025V22.95zM16 19V4.65L9.45 2H20v17z");
}

</style>
