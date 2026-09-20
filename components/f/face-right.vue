<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy3-fbj8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:face-right" /></template>
<style>
.yy3-fbj8u {
  fill: currentColor;
  d: path("M15.327 11.635q-.329 0-.559-.23t-.23-.578t.23-.578t.559-.23q.348 0 .588.23q.239.23.239.578t-.24.578t-.587.23m-4.654 0q-.348 0-.578-.23t-.23-.578t.23-.578t.578-.23t.578.23t.23.578t-.23.578t-.578.23M8.329 15.96q-1.517-.927-2.423-2.495T5 10q0-2.927 2.036-4.963T12 3t4.964 2.036T19 10q0 1.896-.906 3.465t-2.423 2.495l-.738-.72q1.376-.78 2.222-2.156Q18 11.708 18 10q0-.39-.054-.746t-.162-.727q-.269.058-.548.087q-.278.028-.548.028q-1.754.085-3.334-.614q-1.581-.7-2.727-2.024q-.7 1.415-1.905 2.429T6 9.894v.058q-.03 1.714.817 3.11q.848 1.398 2.25 2.179zm3.767 6.444l-.688-.708l2.075-2.1H8.596v-1h4.887l-2.075-2.08l.688-.708l3.308 3.288z");
}

</style>
