<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-kh3dy5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:identity-platform-outline-sharp" /></template>
<style>
.h-kh3dy5t {
  fill: currentColor;
  d: path("M9.871 11.629Q9 10.758 9 9.5t.871-2.129T12 6.5t2.129.871T15 9.5t-.871 2.129T12 12.5t-2.129-.871m3.538-.72Q14 10.317 14 9.5t-.591-1.409Q12.817 7.5 12 7.5t-1.409.591Q10 8.683 10 9.5t.591 1.409q.592.591 1.409.591t1.409-.591M12 21.327l-8-4.885V7.558l8-4.885l8 4.885v8.884zm0-1.152l4.156-2.544q-.946-.547-2-.839Q13.105 16.5 12 16.5t-2.157.292t-1.999.839zm-5.12-3.142q1.155-.716 2.455-1.124T12 15.5t2.666.409q1.3.408 2.453 1.124L19 15.9V8.125L12 3.85L5 8.125V15.9zM12 12");
}

</style>
