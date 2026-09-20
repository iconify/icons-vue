<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d9ogiibcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-read-multiple-20-filled" /></template>
<style>
.d9ogiibcm {
  fill: currentColor;
  d: path("M8.738 2.074a.5.5 0 0 1 .524 0l6.024 3.707q.105.065.195.143L9 9.913L2.519 5.924q.09-.078.195-.143zm7.239 4.72q.023.13.023.265V12.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 2 12.5V7.059q0-.136.024-.265l6.714 4.132a.5.5 0 0 0 .524 0zM4.5 16c.456.607 1.182 1 2 1H14a4 4 0 0 0 4-4V8.059a1.5 1.5 0 0 0-.714-1.278l-.333-.205q.047.238.047.483V13a3 3 0 0 1-3 3z");
}

</style>
