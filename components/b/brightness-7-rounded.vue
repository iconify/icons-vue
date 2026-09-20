<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tev6pesrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-7-rounded" /></template>
<style>
.tev6pesrq {
  fill: currentColor;
  d: path("M9.066 19h-2.45q-.667 0-1.141-.475T5 17.386v-2.451l-1.79-1.803q-.237-.243-.349-.534t-.111-.594q0-.301.112-.596t.347-.538L5 9.066v-2.45q0-.667.475-1.141T6.615 5h2.451l1.803-1.79q.243-.237.534-.349t.594-.111q.301 0 .596.112t.538.347L14.934 5h2.45q.667 0 1.142.475T19 6.615v2.451l1.79 1.803q.237.243.349.534t.111.594q0 .301-.111.596t-.348.538L19 14.934v2.45q0 .667-.475 1.142t-1.14.474h-2.451l-1.803 1.79q-.243.237-.534.349t-.594.111q-.301 0-.596-.111t-.538-.348zm5.924-4.01q1.24-1.242 1.24-2.99t-1.24-2.99Q13.747 7.77 12 7.77T9.01 9.01Q7.77 10.253 7.77 12t1.24 2.99q1.242 1.24 2.99 1.24t2.99-1.24m-5.279-.702Q8.77 13.346 8.77 12t.942-2.289T12 8.77t2.289.942T15.23 12t-.942 2.289T12 15.23t-2.289-.942");
}

</style>
