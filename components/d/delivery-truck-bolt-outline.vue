<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyxmy0aay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:delivery-truck-bolt-outline" /></template>
<style>
.fyxmy0aay {
  fill: currentColor;
  d: path("M4.875 19.125Q4 18.25 4 17H1.5l.45-2h2.825q.425-.475 1-.737T7 14t1.225.263t1 .737H13.4l2.1-9H6.55l.425-2H18l-.925 4H20l3 4l-1 5h-2q0 1.25-.875 2.125T17 20t-2.125-.875T14 17h-4q0 1.25-.875 2.125T7 20t-2.125-.875M15.925 13h4.825l.1-.525L19 10h-2.375zM15.5 6l-2.1 9l.05-.175zm-12 7v-3H1l3.5-5v3H7zM7 18q.425 0 .713-.288T8 17t-.288-.712T7 16t-.712.288T6 17t.288.713T7 18m10 0q.425 0 .713-.288T18 17t-.288-.712T17 16t-.712.288T16 17t.288.713T17 18");
}

</style>
