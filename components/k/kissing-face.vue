<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="y5p7u-b5s"/><ellipse class="zwc45xowa"/><path class="bz9noibav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:kissing-face" /></template>
<style>
.bz9noibav {
  fill: var(--svg-color--664500, #664500);
  d: path("M20.871 28c1.335-.412 2.629-1.156 2.629-2.5c0-2.619-4.912-2.968-5.472-2.999a.493.493 0 0 0-.527.468a.5.5 0 0 0 .464.53c.035.002 3.535.299 3.535 2.001s-3.5 1.999-3.535 2.001c-.013.001-.023.008-.036.01a.5.5 0 0 0-.149.041l-.015.009a.5.5 0 0 0-.127.1q-.019.023-.035.047a.5.5 0 0 0-.06.103q-.016.045-.024.092c-.004.023-.016.044-.018.067l.004.031c.002.015-.005.021-.004.031c.001.024.013.045.018.068c.006.031.011.061.023.09q.02.044.049.084q.024.038.052.071q.035.033.078.061c.024.017.046.034.074.047a.4.4 0 0 0 .101.027c.024.006.044.018.069.02c.035.001 3.535.298 3.535 2s-3.5 1.999-3.535 2.001A.501.501 0 0 0 18 33.5l.028-.001c.56-.031 5.472-.38 5.472-2.999c0-1.344-1.294-2.088-2.629-2.5");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.y5p7u-b5s {
  cx: 12.5px;
  cy: 15.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.zwc45xowa {
  cx: 23.5px;
  cy: 15.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
