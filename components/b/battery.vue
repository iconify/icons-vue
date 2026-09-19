<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="a0zalnbnr"/><path class="i89r3db9q"/></g><path class="bh2i2lbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:battery" /></template>
<style>
.a0zalnbnr {
  d: path("M42 7c0 1.1-.9 2-2 2H24c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h16c1.1 0 2 .9 2 2z");
}

.bh2i2lbuv {
  fill: var(--svg-color--a8d600, #a8d600);
  d: path("M46 24c0 1.1-.9 2-2 2H20c-1.1 0-2-.9-2-2v-4c0-1.1.9-2 2-2h24c1.1 0 2 .9 2 2zm0 12c0 1.1-.9 2-2 2H20c-1.1 0-2-.9-2-2v-4c0-1.1.9-2 2-2h24c1.1 0 2 .9 2 2zm0 12c0 1.1-.9 2-2 2H20c-1.1 0-2-.9-2-2v-4c0-1.1.9-2 2-2h24c1.1 0 2 .9 2 2z");
}

.i89r3db9q {
  d: path("M48 6H16c-2.2 0-4 1.8-4 4v48c0 2.2 1.8 4 4 4h32c2.2 0 4-1.8 4-4V10c0-2.2-1.8-4-4-4m0 47c0 .5-.5 1-1 1H17c-.5 0-1-.5-1-1V15c0-.5.5-1 1-1h30c.5 0 1 .5 1 1z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

</style>
