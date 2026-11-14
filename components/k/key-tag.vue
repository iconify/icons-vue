<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcs9zv0dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:key-tag" /></template>
<style>
.rcs9zv0dn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.25h7q.149 0 .287.057t.243.163l9.5 9.5q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-1 1q-.105.106-.243.163T20 14.25h-5.75Q13 14.25 13 15.5v5q0 .093-.023.182q-.022.09-.066.172q-.043.082-.106.15q-.062.069-.139.12l-.75.5q-.056.037-.117.064t-.127.042t-.133.019t-.134-.005t-.13-.029t-.124-.051q-.059-.031-.112-.073t-.098-.091l-8.5-9.5q-.092-.103-.142-.232q-.049-.13-.049-.268v-7q0-.932.659-1.591T4.5 2.25m13.5 12q3.75 0 3.75 3.75T18 21.75T14.25 18T18 14.25M7.75 5.5Q5.5 5.5 5.5 7.75T7.75 10T10 7.75T7.75 5.5");
}

</style>
