<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbm5q4bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-home-rounded" /></template>
<style>
.xbm5q4bnm {
  fill: currentColor;
  d: path("M13.77 13.77q.73-.732.73-1.77t-.73-1.77T12 9.5t-1.77.73T9.5 12t.73 1.77t1.77.73t1.77-.73m-1.828 2.153q-1.45 0-2.812.451t-2.55 1.303q-.222.156-.401.36T6 18.514v.063q0 .192.144.308T6.5 19h11q.212 0 .356-.125t.144-.317v-.045q0-.273-.179-.486q-.179-.214-.402-.37q-1.206-.851-2.597-1.293t-2.88-.441M6.616 20q-.672 0-1.144-.472T5 18.385v-8.077q0-.38.174-.727t.472-.565l5.385-4.058q.429-.324.969-.324t.97.324l5.384 4.057q.298.218.472.566t.174.727v8.077q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
