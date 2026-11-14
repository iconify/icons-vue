<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3tbacao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-pit" /></template>
<style>
.yd3tbacao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 13.25q-4.75 0-4.75-4.5q0-1.589 1.481-3.791q1.085-1.613 1.284-2.606q.014-.073.042-.141t.07-.129t.093-.114q.053-.052.114-.093t.13-.069q.068-.028.14-.043t.147-.014t.146.015q.187.037.333.159q1.642 1.368 2.214 3.002q.219-.421.328-.858q.018-.072.05-.138q.031-.067.075-.126q.044-.06.099-.109q.055-.05.118-.088t.133-.063t.143-.036t.146-.007q.074.003.146.021q.237.06.394.248q1.674 2.008 1.674 4.98q0 4.5-4.75 4.5m9.75 1.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 13.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 3.153 2.973 5.039Q7.918 21.25 12 21.25t6.777-1.711q2.973-1.886 2.973-5.039");
}

</style>
