<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lo4_0kg6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:box-20-filled" /></template>
<style>
.lo4_0kg6c {
  fill: currentColor;
  d: path("m10 7.96l3.029-1.21l-7.5-3l-2.586 1.034a1.5 1.5 0 0 0-.364.208zM2.035 5.853A1.5 1.5 0 0 0 2 6.176v7.646a1.5 1.5 0 0 0 .943 1.393L8.7 17.518q.391.156.8.214V8.838zm8.465 11.88a3.5 3.5 0 0 0 .8-.214l5.757-2.303A1.5 1.5 0 0 0 18 13.822V6.176q0-.166-.035-.324L10.5 8.838zm6.921-12.74l-3.046 1.219l-7.5-3L8.7 2.48a3.5 3.5 0 0 1 2.6 0l5.757 2.303a1.5 1.5 0 0 1 .364.208");
}

</style>
