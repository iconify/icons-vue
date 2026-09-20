<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0n-f1b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:borg" /></template>
<style>
.e0n-f1b3z {
  fill: currentColor;
  d: path("M11 21.725L4 17.7q-.475-.275-.737-.737T3 15.95V13h5v3h3zM3 11V8.05q0-.55.263-1.012T4 6.3l7-4.025V8H8v3zm7 3v-4h4v4zm3 7.725V16h3v-3h5v2.95q0 .55-.262 1.013T20 17.7zM16 11V8h-3V2.275L20 6.3q.475.275.738.738T21 8.05V11z");
}

</style>
