<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwj3wv_8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:artist-rounded" /></template>
<style>
.hwj3wv_8c {
  fill: currentColor;
  d: path("M16.08 18.035q-.58-.581-.58-1.42q0-.838.58-1.419t1.42-.58q.316 0 .594.095q.279.095.521.297v-4.354q0-.348.23-.578t.578-.23h1.308q.31 0 .54.22q.229.22.229.55q0 .309-.23.539t-.54.23H19.5v5.23q0 .839-.58 1.42q-.581.58-1.42.58t-1.42-.58m-7.703-7.527Q7.5 9.63 7.5 8.385t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m-4.07 8.108q-.347 0-.577-.23t-.23-.578v-.839q0-.625.36-1.161q.361-.537.97-.835q1.455-.698 2.853-1.028t2.817-.33q.585 0 1.128.046q.543.047 1.07.158q.348.062.49.39q.14.33-.036.66q-.217.433-.316.891q-.1.46-.1.932q0 .248.028.493q.028.246.09.474q.087.374-.122.665t-.557.291z");
}

</style>
