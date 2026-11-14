<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly46az05z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hurricane-lantern" /></template>
<style>
.ly46az05z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25Q9.25 2.25 9.25 5q0 .721.189 1.252q-.161.014-.301.091q-.141.078-.238.207l-1.5 2q-.09.119-.127.264q-.037.144-.015.292q.018.132.082.249q-1.09 1.808-1.09 4.145q0 2.176.945 3.894q-1.445.455-1.445 2.356q0 1.036.732 1.768t1.768.732h7.5q1.036 0 1.768-.732t.732-1.768q0-1.901-1.445-2.356q.945-1.718.945-3.894q0-2.337-1.09-4.145q.09-.166.09-.355q0-.122-.038-.237q-.039-.116-.112-.213l-1.5-2q-.097-.129-.238-.207t-.301-.09q.189-.532.189-1.253q0-2.75-2.75-2.75m1.5 7.5v7.5h-3v-7.5zm1.5 7.5v-7.5h.127q1.123 1.584 1.123 3.75t-1.123 3.75zm-6.127-7.5H9v7.5h-.127Q7.75 15.666 7.75 13.5t1.123-3.75");
}

</style>
