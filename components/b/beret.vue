<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmt2pwycp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beret" /></template>
<style>
.wmt2pwycp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 5.769V4.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q11.926 3.5 12 3.5t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13q.028.068.043.141t.014.146v1.519q3.998.21 6.582 2.69q3.059 2.936 1.339 6.376q-.047.094-.117.171t-.16.132q-.089.055-.189.083q-.101.029-.205.029h-1.804q.054.285.054.625Q18.25 18 16.125 18h-8.25Q5.75 18 5.75 15.875q0-.34.054-.625H4q-.104 0-.205-.029q-.1-.028-.189-.083t-.16-.132t-.117-.171q-1.72-3.44 1.339-6.376q2.584-2.48 6.582-2.69");
}

</style>
