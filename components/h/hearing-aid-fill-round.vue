<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g33popj4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-aid-fill-round" /></template>
<style>
.g33popj4i {
  fill: currentColor;
  d: path("M3 11a9 9 0 0 1 9-9a9 9 0 0 1 9 9c-.001 1.483-.584 2.686-1.798 3.55c-.965.686-2.122 1.038-3.241 1.384c-.438.136-.879.27-1.309.432a5 5 0 0 0-.977.47c-.442.29-.675.624-.675 1.164a4 4 0 0 1-8 0a1 1 0 0 1 2 0a2 2 0 0 0 4 0c.001-1.23.559-2.168 1.579-2.837c.844-.553 1.836-.844 2.792-1.14c.502-.155 1.007-.309 1.496-.501c.706-.275 1.496-.66 1.873-1.355c.193-.356.26-.766.26-1.167a7.002 7.002 0 0 0-14 0a1 1 0 0 1-2 0m10 .829V12a1 1 0 0 1-.553.894l-2 1a1 1 0 1 1-.894-1.788l.978-.489a3.001 3.001 0 1 1 2.469.212M13 9a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

</style>
