<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy4rtrbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camp-axe" /></template>
<style>
.yy4rtrbts {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.497 6.294l9.75-3.5q.069-.025.142-.036t.147-.007t.145.021t.139.05q.067.031.126.075q.06.044.109.099q.05.054.088.118q.038.063.063.133q.05.14.043.289t-.071.284t-.174.235t-.251.151l-9.3 3.339q.299.368.425.872l.884 3.537q.172.69-.05 1.296H19.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.5q0 1.405-2.753 2.139q-2.292.611-5.497.611q-8.25 0-8.25-2.75V14q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.666q-.194-.536-.082-1.152l.522-2.876q.234-1.285 1.466-1.719l1.874-.661q.562-.199 1.103-.109q.01-.027.023-.053q.063-.135.174-.235t.251-.151");
}

</style>
