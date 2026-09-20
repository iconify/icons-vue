<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi-drtbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cancel-schedule-send-outline-rounded" /></template>
<style>
.yi-drtbge {
  fill: currentColor;
  d: path("m16.802 17.167l1.471 1.472q.112.111.27.12q.157.01.288-.12t.13-.28q0-.147-.13-.278l-1.465-1.465l1.47-1.472q.112-.111.122-.269t-.121-.288t-.28-.131q-.147 0-.278.13l-1.471 1.472l-1.471-1.471q-.112-.112-.27-.121q-.157-.01-.288.12t-.131.28t.13.278l1.472 1.472l-1.477 1.476q-.111.112-.121.264t.121.282t.279.131t.279-.13zm-12.61.14V6.617q0-.454.361-.694q.36-.24.764-.058L14.966 10q.244.104.296.299t-.022.372t-.25.281t-.44 0L5.192 7v3.885l2.274.524q.236.056.354.218t.12.373t-.119.373t-.354.217l-2.274.525V17l5.13-2.171q.224-.104.398-.013q.174.092.247.268q.073.178.021.373t-.296.299l-5.369 2.303q-.404.181-.767-.058t-.364-.693m9.78 2.143q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165M9.444 12");
}

</style>
