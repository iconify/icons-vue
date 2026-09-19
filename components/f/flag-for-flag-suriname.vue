<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="meksqud1v"/><path class="ui763ubxk"/><path class="bt_6j3blz"/><path class="tqa9a94nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-suriname" /></template>
<style>
.bt_6j3blz {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m32 37.3l6.2 4.7l-2.4-7.6l6.2-4.8h-7.6L32 22l-2.4 7.6H22l6.2 4.8l-2.4 7.6z");
}

.meksqud1v {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M2 32c0 3.9.7 7.6 2.1 11h55.8c1.3-3.4 2.1-7.1 2.1-11s-.7-7.6-2.1-11H4.1C2.7 24.4 2 28.1 2 32");
}

.tqa9a94nm {
  fill: var(--svg-color--699635, #699635);
  d: path("M56.7 15C51.3 7.2 42.3 2 32 2S12.7 7.2 7.3 15zM7.3 49c5.4 7.8 14.5 13 24.7 13s19.3-5.2 24.7-13z");
}

.ui763ubxk {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.3 49h49.4c1.3-1.9 2.4-3.9 3.2-6H4.1c.8 2.1 1.9 4.1 3.2 6M4.1 21h55.8c-.8-2.1-1.9-4.1-3.2-6H7.3c-1.3 1.9-2.4 3.9-3.2 6");
}

</style>
