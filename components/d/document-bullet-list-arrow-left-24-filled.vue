<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgxvi0bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-bullet-list-arrow-left-24-filled" /></template>
<style>
.mgxvi0bnm {
  fill: currentColor;
  d: path("M12 8V2H6a2 2 0 0 0-2 2v7.498A6.5 6.5 0 0 1 6.5 11a6.47 6.47 0 0 1 3.53 1.04a.75.75 0 0 1 .72-.54h5.5a.75.75 0 0 1 0 1.5h-5.06c.427.444.79.949 1.078 1.5h3.982a.75.75 0 0 1 0 1.5h-3.424q.172.724.174 1.5h3.25a.75.75 0 0 1 0 1.5h-3.424a6.5 6.5 0 0 1-1.636 3H18a2 2 0 0 0 2-2V10h-6a2 2 0 0 1-2-2m1.5 0V2.5l6 6H14a.5.5 0 0 1-.5-.5m-7 15a5.5 5.5 0 1 1 0-11a5.5 5.5 0 0 1 0 11m3-5a.5.5 0 0 0 0-1H4.707l1.647-1.646a.5.5 0 0 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L4.707 18z");
}

</style>
