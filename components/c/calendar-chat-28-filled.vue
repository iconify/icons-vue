<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="j_vf-c9zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-28-filled" /></template>
<style>
.j_vf-c9zq {
  fill: currentColor;
  d: path("M20.505 14a6.5 6.5 0 1 1-3.148 12.189l-2.716.79a.5.5 0 0 1-.62-.62l.794-2.714A6.5 6.5 0 0 1 20.505 14m4.495.495a7.5 7.5 0 0 0-11.256 9.254L13.378 25H6.25A3.25 3.25 0 0 1 3 21.75V9.5h22zM18.005 21a.5.5 0 1 0 0 1h2.5a.5.5 0 0 0 0-1zm0-2a.5.5 0 1 0 0 1h5a.5.5 0 0 0 0-1zM21.75 3A3.25 3.25 0 0 1 25 6.25V8H3V6.25A3.25 3.25 0 0 1 6.25 3z");
}

</style>
