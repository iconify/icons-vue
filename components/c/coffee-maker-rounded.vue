<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj51phbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:coffee-maker-rounded" /></template>
<style>
.oj51phbgw {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H18.5q.214 0 .357.143T19 3.5t-.143.357T18.5 4h-2v1.154q0 .329-.22.549t-.55.22H9.27q-.33 0-.55-.22t-.22-.55V4H6.616q-.27 0-.443.173T6 4.616v14.769q0 .269.173.442t.443.173h3.896q-.893-.54-1.453-1.395q-.559-.855-.559-2.067v-2.384q0-.671.472-1.144t1.144-.472h4.768q.672 0 1.144.472q.472.473.472 1.144v2.385q0 1.211-.56 2.066T14.49 20h4.01q.214 0 .357.143T19 20.5t-.143.357T18.5 21zM13.04 9.77q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54t.54.229t.54-.23");
}

</style>
