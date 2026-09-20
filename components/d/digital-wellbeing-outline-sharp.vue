<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt25xfbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:digital-wellbeing-outline-sharp" /></template>
<style>
.jt25xfbso {
  fill: currentColor;
  d: path("M10.064 8.09q-.795-.794-.795-1.936t.795-1.937T12 3.423t1.937.794t.794 1.937t-.794 1.936T12 8.885t-1.936-.794m3.162-.71q.505-.505.505-1.226t-.505-1.226T12 4.423t-1.226.505t-.505 1.226t.505 1.226T12 7.885t1.226-.505M12 20.27l-5.461-5.462q-.385-.385-.577-.885t-.193-1.084q0-1.148.79-1.936t1.941-.787q.56 0 1.034.207q.474.208.878.612L12 12.523l1.589-1.588q.384-.385.871-.602t1.048-.217q1.14 0 1.932.788q.79.788.79 1.935q0 .584-.191 1.084t-.578.885zm0-1.428l4.742-4.742q.264-.263.376-.58q.113-.316.113-.664q0-.696-.502-1.218t-1.231-.522q-.336 0-.613.104t-.539.372L12 13.938l-2.308-2.307q-.182-.194-.47-.355q-.29-.16-.714-.16q-.735 0-1.237.517T6.77 12.84q0 .345.115.665q.116.32.374.583zm0-3.863");
}

</style>
