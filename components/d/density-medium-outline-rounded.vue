<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzi5dkb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:density-medium-outline-rounded" /></template>
<style>
.uzi5dkb9t {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21zm0-8q-.425 0-.712-.288T3 12t.288-.712T4 11h16q.425 0 .713.288T21 12t-.288.713T20 13zm0-8q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5z");
}

</style>
