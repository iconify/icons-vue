<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up_fsr2oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crossbuck-sign" /></template>
<style>
.up_fsr2oe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.078 8.25l-2.693 1.886q-1.843 1.291-.552 3.133t3.133.552l3.284-2.299V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-9.978l3.284 2.299q1.842 1.291 3.133-.552t-.552-3.133L15.922 8.25l2.693-1.886q1.843-1.291.552-3.133t-3.133-.552L12 5.503L7.966 2.679q-1.842-1.291-3.133.552t.552 3.133z");
}

</style>
