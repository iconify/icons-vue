<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs5ngx46m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hotel-outline-sharp" /></template>
<style>
.bs5ngx46m {
  fill: currentColor;
  d: path("M1 19V4h2v10h8V6h12v13h-2v-3H3v3zm3.875-6.875Q4 11.25 4 10t.875-2.125T7 7t2.125.875T10 10t-.875 2.125T7 13t-2.125-.875M13 14h8V8h-8zm-5.287-3.287Q8 10.425 8 10t-.288-.712T7 9t-.712.288T6 10t.288.713T7 11t.713-.288M13 8v6z");
}

</style>
