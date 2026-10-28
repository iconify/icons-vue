<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s34idwb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-person-outline-rounded" /></template>
<style>
.s34idwb_x {
  fill: currentColor;
  d: path("M4 6v12v-7.808v.39zm.616 13q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.576q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V6.904l-7.123 4.638q-.404.262-.877.262t-.877-.262L4 6.904v10.48q0 .27.173.443t.443.173h7.038q.213 0 .356.143t.144.357t-.144.357t-.356.143zm13.153-3.423q-.632 0-1.066-.434t-.434-1.066t.434-1.066t1.066-.434t1.067.434t.433 1.066t-.433 1.066q-.434.434-1.067.434M12 11l7.692-5H4.308zm5.773 6q.604 0 1.212.128q.607.128 1.161.409q.327.148.584.397t.257.606q0 .197-.151.328t-.367.132h-5.432q-.196 0-.335-.132t-.138-.327q0-.339.244-.6q.244-.262.57-.404q.56-.275 1.173-.406T17.773 17");
}

</style>
