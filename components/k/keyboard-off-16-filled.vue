<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5suycwpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-off-16-filled" /></template>
<style>
.v5suycwpf {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L12.293 13H2.75A1.75 1.75 0 0 1 1 11.25v-6.5a1.75 1.75 0 0 1 1.342-1.701L1.146 1.854a.5.5 0 0 1 0-.707M13.25 3c.966 0 1.75.784 1.75 1.75v6.5c0 .452-.173.863-.455 1.174l-3.439-3.439a.75.75 0 1 0-.593-.593L9.107 6.986a.75.75 0 1 0-.593-.593L5.122 3zM3.5 10a.5.5 0 0 0 0 1h6.793l-1-1zm1.75-2.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m-2-2a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m9 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
