<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pcg88plrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-32-filled" /></template>
<style>
.pcg88plrq {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14s-6.268 14-14 14c-2.368 0-4.602-.59-6.56-1.629l-5.528 1.572a1.5 1.5 0 0 1-1.853-1.853l1.571-5.528A13.94 13.94 0 0 1 2 16C2 8.268 8.27 2 16 2m6.707 9.293a1 1 0 0 0-1.415 0l-6.794 6.793l-3.291-3.291a1 1 0 0 0-1.414 1.414l3.998 3.998a1 1 0 0 0 1.414 0l7.502-7.5a1 1 0 0 0 0-1.414");
}

</style>
