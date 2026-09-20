<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhelk89w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-and-garden-rounded" /></template>
<style>
.thhelk89w {
  fill: currentColor;
  d: path("M6.616 19q-.672 0-1.144-.472T5 17.385V9.452l-2 1.486q-.171.116-.363.095q-.19-.022-.325-.199q-.135-.17-.111-.359t.195-.323l8.654-6.438q.217-.162.463-.233t.493-.072t.5.072t.469.232l7.225 5.38q.34.253.18.65q-.16.395-.582.32q-.554-.017-1.13.1t-1.168.366q-1.616-.69-3.107-.359t-2.691 1.532t-1.532 2.682t.359 3.116q-.092.227-.163.444q-.072.218-.116.45q-.063.254-.262.43T9.516 19zM17.5 21.76q-1.127.782-2.207.747t-1.922-.878q-.842-.842-.878-1.932q-.035-1.09.747-2.197q-.782-1.127-.747-2.207t.878-1.922t1.932-.878q1.09-.035 2.197.748q1.127-.783 2.207-.748t1.922.878t.878 1.932t-.748 2.197q.783 1.127.748 2.207t-.878 1.922t-1.932.878t-2.197-.747m.56-3.7q.229-.227.229-.56t-.228-.56q-.228-.229-.561-.229t-.56.228t-.229.561t.228.56q.228.229.561.229t.56-.228");
}

</style>
