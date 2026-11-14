<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy0gc6b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-iron" /></template>
<style>
.qy0gc6b1b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.617 2.927L10.81 15.648l1.418 5.67q.018.072.021.146q.004.073-.007.146t-.036.143t-.063.133t-.088.118t-.109.099t-.126.075q-.066.032-.138.05q-.09.022-.182.022h-8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3q0-.107.03-.211q.03-.103.088-.193t.139-.161t.179-.116L9.5 14.905l8.883-12.832q.085-.123.211-.203q.125-.081.272-.108t.292.005q.146.031.269.116q.061.042.112.095q.051.054.091.116t.068.13q.027.069.04.142t.012.146t-.017.146t-.045.14t-.071.129M4.25 18.98v1.77h6.289l-1.047-4.19z");
}

</style>
