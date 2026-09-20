<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unp_r6d7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-off-sharp" /></template>
<style>
.unp_r6d7n {
  fill: currentColor;
  d: path("M20.429 21.856L17.573 19H3V5h2l1 1H4.573L2.606 4.033l.713-.714l17.823 17.823zM21 18.188l-7.221-7.22L20 6.884L19.692 6l-6.58 4.3l-5.3-5.3H21z");
}

</style>
