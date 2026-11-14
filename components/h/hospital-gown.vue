<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy3bvpp6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hospital-gown" /></template>
<style>
.cy3bvpp6d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.504 3.353l-1.65-.943q-1.404-.801-2.71.149L3.878 4.935q-1.883 1.37-.649 3.345l1.157 1.853q.364.584 1.037.728q.403.087.77-.016l-.366 8.801q-.045 1.065.693 1.834t1.804.77h7.352q1.066 0 1.804-.77q.738-.769.693-1.834l-.366-8.801q.367.103.77.016q.673-.144 1.037-.728l1.157-1.853q1.234-1.975-.649-3.346L16.856 2.56q-1.306-.951-2.71-.15l-1.65.943q-.496.283-.992 0M8 11q0-2 2-2t2 2t-2 2t-2-2m6.25 1q.828 0 1.414.586T16.25 14t-.586 1.414T14.25 16q-2 0-2-2t2-2m-6 5.501v-.002q0-.828.585-1.414q.586-.586 1.415-.586t1.415.586q.586.587.585 1.414q.001.829-.585 1.416q-.586.586-1.415.586t-1.415-.586t-.585-1.414");
}

</style>
