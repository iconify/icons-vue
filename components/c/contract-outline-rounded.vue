<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8674ibpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contract-outline-rounded" /></template>
<style>
.b8674ibpo {
  fill: currentColor;
  d: path("M6 21q-.846 0-1.423-.577T4 19v-1.154q0-.671.472-1.143t1.143-.472H7V4.616q0-.672.472-1.144T8.616 3h9.769q.67 0 1.143.472q.472.472.472 1.144V19q0 .846-.577 1.423T18 21zm12-1q.425 0 .713-.288T19 19V4.616q0-.27-.173-.443T18.385 4h-9.77q-.269 0-.442.173T8 4.616V16.23h7.385q.67 0 1.143.472q.472.472.472 1.143V19q0 .425.288.713T18 20M9.885 8.385q-.214 0-.357-.144q-.144-.143-.144-.356q0-.214.144-.357q.143-.143.357-.143h7.23q.214 0 .357.143q.144.143.144.357q0 .213-.144.356q-.143.144-.357.144zm0 2.769q-.214 0-.357-.143q-.144-.144-.144-.357t.144-.357t.357-.143h7.23q.214 0 .357.143q.144.144.144.357t-.144.357t-.357.143zM6 20h10v-2.154q0-.269-.173-.442t-.442-.173h-9.77q-.269 0-.442.173T5 17.846V19q0 .425.288.713T6 20m0 0H5h11z");
}

</style>
