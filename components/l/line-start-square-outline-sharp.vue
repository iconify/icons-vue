<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prx_zibmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-square-outline-sharp" /></template>
<style>
.prx_zibmv {
  fill: currentColor;
  d: path("M4 15.5h7v-7H4zm9 2H2v-11h11V11h9v2h-9zM7.5 12");
}

</style>
