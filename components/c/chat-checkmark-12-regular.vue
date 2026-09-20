<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hk6xnqiec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-12-regular" /></template>
<style>
.hk6xnqiec {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1-2.41 9.382l-1.944.593a.5.5 0 0 1-.625-.624l.593-1.948A5 5 0 0 1 6 1m0 1a4 4 0 0 0-3.417 6.08a.5.5 0 0 1 .052.406L2.25 9.744l1.257-.382a.5.5 0 0 1 .407.052A4 4 0 1 0 6 2m1.646 2.396a.5.5 0 0 1 .708.708l-2.5 2.5a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 0 1 .708-.708L5.5 6.543z");
}

</style>
