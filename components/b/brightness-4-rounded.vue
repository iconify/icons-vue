<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zistxacfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-4-rounded" /></template>
<style>
.zistxacfh {
  fill: currentColor;
  d: path("M12.53 16.23q1.757 0 2.994-1.24q1.238-1.242 1.238-2.99t-1.238-2.99q-1.237-1.24-2.993-1.24h-.348q-.166 0-.323.05q-.313.061-.396.363t.153.483q.791.59 1.207 1.466T13.241 12q0 .989-.408 1.878q-.408.89-1.216 1.456q-.242.182-.174.49q.068.309.398.351q.161.05.335.053t.355.003M9.066 19h-2.45q-.667 0-1.141-.475T5 17.386v-2.451l-1.79-1.803q-.237-.243-.349-.534t-.111-.594q0-.301.112-.596t.347-.538L5 9.066v-2.45q0-.667.475-1.141T6.615 5h2.451l1.803-1.79q.243-.237.534-.349t.594-.111q.301 0 .596.112t.538.347L14.934 5h2.45q.667 0 1.142.475T19 6.615v2.451l1.79 1.803q.237.243.349.534t.111.594q0 .301-.111.596t-.348.538L19 14.934v2.45q0 .667-.475 1.142t-1.14.474h-2.451l-1.803 1.79q-.243.237-.534.349t-.594.111q-.301 0-.596-.111t-.538-.348z");
}

</style>
