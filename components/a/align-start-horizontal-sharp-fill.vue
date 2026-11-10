<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izjajxcrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-horizontal-sharp-fill" /></template>
<style>
.izjajxcrr {
  fill: currentColor;
  d: path("M10 5C10.552 5 11 5.448 11 6V22C11 22.552 10.552 23 10 23H4C3.448 23 3 22.552 3 22V6C3 5.448 3.448 5 4 5H10ZM20 5C20.552 5 21 5.448 21 6V14C21 14.552 20.552 15 20 15H14C13.448 15 13 14.552 13 14V6C13 5.448 13.448 5 14 5H20ZM23 1V3H1V1H23Z");
}

</style>
