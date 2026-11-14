<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3z_3jbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:build-flags" /></template>
<style>
.h3z_3jbjb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 4.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.75 21v-6.53q1.282-.49 3.523.127q2.858.786 4.506.099q2.633-1.053 5.458.006q.127.048.263.048q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V4.5q0-.115-.034-.224t-.1-.203q-.065-.094-.155-.165q-.09-.07-.198-.11q-3.369-1.264-6.551.01q-1.181.492-3.541-.158q-3.195-.879-5.049.202q-.085.05-.154.119q-.069.07-.118.155q-.049.086-.075.181T4.25 4.5");
}

</style>
