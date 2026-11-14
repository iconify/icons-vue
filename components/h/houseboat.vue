<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piei57bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:houseboat" /></template>
<style>
.piei57bnu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.252 6.931Q5.25 7.599 5.25 8.803V14.5q0 .413.076.75H3q-.215 0-.397.114q-.127.079-.214.201q-.086.121-.12.266q-.033.146-.009.293q.025.147.104.273l2.5 4q.051.081.12.147t.152.112t.176.07t.188.024h13q.095 0 .188-.024q.092-.024.176-.07t.152-.112t.12-.147l2.5-4q.114-.182.114-.397q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15.25h-2.326q.076-.337.076-.75V8.803q0-1.204-1.002-1.872l-4.5-3q-1.248-.832-2.496 0z");
}

</style>
