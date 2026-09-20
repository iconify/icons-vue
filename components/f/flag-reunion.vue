<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gp16xd2jq"/><path class="ph0dgkb3y"/><path class="z4bl3lbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-reunion" /></template>
<style>
.gp16xd2jq {
  fill: var(--svg-color--36f, #36f);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.ph0dgkb3y {
  fill: var(--svg-color--red, red);
  d: path("M18 18L1.368 30.012l.001.001A3.98 3.98 0 0 0 4 31h28a3.98 3.98 0 0 0 2.632-.988z");
}

.z4bl3lbee {
  fill: var(--svg-color--ff0, #ff0);
  d: path("m18 18.019l18 1.487v-2.975zM0 16.531v2.975l18-1.487zm2.405-11.2A4 4 0 0 0 .404 7.247L18 18L2.406 5.33zm33.191 1.916a4.02 4.02 0 0 0-2.003-1.917L18 18zM19.5 5h-3L18 18z");
}

</style>
