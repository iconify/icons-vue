<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un5bvrbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:conditions-sharp" /></template>
<style>
.un5bvrbaq {
  fill: currentColor;
  d: path("M8.809 5.307q-.501-.501-.501-1.191t.5-1.192Q9.31 2.423 10 2.423t1.191.501t.501 1.192t-.5 1.19q-.502.502-1.192.502t-1.191-.501m9.678 12.18q.82-.821.82-1.987t-.82-1.986q-.821-.822-1.987-.822t-1.986.822t-.822 1.986t.822 1.987q.82.82 1.986.82t1.987-.82m3.113 3.802l-2.777-2.777q-.512.388-1.102.592t-1.221.204q-1.586 0-2.697-1.111t-1.11-2.697t1.11-2.697t2.697-1.11t2.697 1.11t1.11 2.697q0 .63-.203 1.221q-.204.59-.593 1.102L22.29 20.6zm-10.408.211v-2.813q.202.35.455.648t.545.563V21.5zm-3.384 0V8.423q-1.467-.125-2.92-.324T2 7.539l.23-1q1.928.478 3.858.681T10 7.423t3.913-.203q1.93-.203 3.856-.681l.231 1q-1.436.361-2.888.56t-2.92.324v2.679q-.811.76-1.31 1.803q-.497 1.043-.555 2.249v.058q0 .029.006.057H8.808V21.5z");
}

</style>
