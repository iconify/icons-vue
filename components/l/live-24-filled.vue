<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc2mh746a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-24-filled" /></template>
<style>
.yc2mh746a {
  fill: currentColor;
  d: path("M4.93 4.929a1 1 0 0 1 1.415 1.414a8 8 0 0 0 0 11.313a1 1 0 0 1-1.414 1.415c-3.906-3.905-3.906-10.237 0-14.142m12.728 0a1 1 0 0 1 1.414 0c3.906 3.905 3.906 10.237 0 14.142a1 1 0 0 1-1.414-1.415a8 8 0 0 0 0-11.313a1 1 0 0 1 0-1.414m-9.9 2.828A1 1 0 0 1 9.174 9.17a4 4 0 0 0 0 5.657a1 1 0 0 1-1.414 1.414a6 6 0 0 1 0-8.485m7.071 0a1 1 0 0 1 1.414 0a6 6 0 0 1 0 8.485a1 1 0 0 1-1.414-1.414a4 4 0 0 0 0-5.657a1 1 0 0 1 0-1.414M12 10.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
