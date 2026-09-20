<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ae0djkils"/><path class="pu7dt2syj"/><path class="ddxd92-7s"/><path class="v2dnvvbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-chile" /></template>
<style>
.ae0djkils {
  fill: var(--svg-color--1f429b, #1f429b);
  d: path("M13 5H4a4 4 0 0 0-4 4v9h13zm-4.663 9.292l-1.882-1.367l-1.882 1.367l.719-2.212l-1.882-1.368h2.326L6.455 8.5l.719 2.212H9.5L7.618 12.08z");
}

.ddxd92-7s {
  fill: var(--svg-color--d42d27, #d42d27);
  d: path("M0 18v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9z");
}

.pu7dt2syj {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H13v13h23V9a4 4 0 0 0-4-4");
}

.v2dnvvbqt {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.174 10.712L6.455 8.5l-.719 2.212H3.41l1.882 1.368l-.719 2.212l1.882-1.367l1.882 1.367l-.719-2.212L9.5 10.712z");
}

</style>
