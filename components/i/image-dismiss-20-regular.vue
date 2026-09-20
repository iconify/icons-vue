<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tr15r5bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-dismiss-20-regular" /></template>
<style>
.tr15r5bsr {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-3.602q.476.244 1 .393V14c0 .373.102.722.28 1.02l4.668-4.588a1.5 1.5 0 0 1 2.104 0l4.669 4.589A2 2 0 0 0 16 14V6a2 2 0 0 0-2-2h-3.208a5.5 5.5 0 0 0-.394-1zm-3.65 8.146a.5.5 0 0 0-.7 0l-4.662 4.58A2 2 0 0 0 6 16h8c.37 0 .715-.1 1.012-.274zM5.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m7 5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m0 1a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1M7.354 3.646a.5.5 0 0 0-.708 0L5.5 4.793L4.354 3.646a.5.5 0 1 0-.708.708L4.793 5.5L3.646 6.646a.5.5 0 1 0 .708.708L5.5 6.207l1.146 1.147a.5.5 0 1 0 .708-.708L6.207 5.5l1.147-1.146a.5.5 0 0 0 0-.708");
}

</style>
