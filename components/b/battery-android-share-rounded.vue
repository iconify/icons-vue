<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux1kn3rui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-share-rounded" /></template>
<style>
.ux1kn3rui {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h11.75q.675 0 .938.613T16.475 7.7l-1.3 1.3q-1.725 0-2.95 1.113T11 13v4q0 .425-.288.713T10 18zm9.288-2.287Q13 15.425 13 15v-2q0-.825.588-1.412T15 11h4.175l-.875-.9q-.275-.3-.275-.712T18.3 8.7q.3-.3.713-.288t.687.288l2.6 2.6q.3.3.3.7t-.3.7l-2.575 2.575q-.3.3-.712.3t-.713-.3t-.3-.7t.3-.7l.875-.875H15v2q0 .425-.288.713T14 16t-.712-.288");
}

</style>
