<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_dvs-b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:coffee-maker" /></template>
<style>
.o_dvs-b3f {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H19v1h-2.5v1.154q0 .329-.22.549t-.55.22H9.27q-.33 0-.55-.22t-.22-.55V4H6.616q-.27 0-.443.173T6 4.616v14.769q0 .269.173.442t.443.173h3.896q-.893-.54-1.453-1.395q-.559-.855-.559-2.067v-4h8v4q0 1.212-.56 2.067q-.56.854-1.451 1.395H19v1zM13.04 9.77q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54t.54.229t.54-.23");
}

</style>
