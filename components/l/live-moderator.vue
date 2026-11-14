<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3unqzt6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:live-moderator" /></template>
<style>
.l3unqzt6z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm5.721 2.783l3.25 1q.057.018.11.044q.054.027.103.061q.048.035.091.077t.078.089t.063.102t.046.109q.019.057.029.116q.009.059.009.119v2.5q0 3.051-3.737 4.452q-.127.048-.263.048t-.263-.048Q8 12.801 8 9.75v-2.5q0-.06.009-.119q.01-.059.029-.116q.018-.056.046-.109q.027-.054.063-.102q.035-.048.078-.089q.043-.042.091-.077q.049-.034.103-.061t.11-.044l3.25-1q.221-.068.442 0");
}

</style>
