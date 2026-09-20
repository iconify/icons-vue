<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymtvc9b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forward-5" /></template>
<style>
.ymtvc9b7p {
  fill: currentColor;
  d: path("M8.882 20.374q-1.455-.626-2.542-1.713t-1.714-2.542T4 13.001t.626-3.12T6.34 7.34t2.54-1.714T12 5h.38l-1.664-1.666l.707-.719l2.885 2.866l-2.846 2.865l-.708-.719L12.38 6H12Q9.075 6 7.038 8.038T5 13t2.038 4.963T12 20t4.963-2.037T19 13h1q0 1.665-.626 3.119t-1.714 2.542t-2.54 1.713T12 21t-3.12-.626m.927-4.682v-.884h3v-1.424h-3v-3.076h3.884v.884h-3v1.424H13q.294 0 .493.199t.2.493V15q0 .294-.2.493t-.493.2z");
}

</style>
