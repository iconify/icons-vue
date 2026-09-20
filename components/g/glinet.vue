<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bz4_8gb_a"/><path class="mmthbxgpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glinet" /></template>
<style>
.bz4_8gb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.254 18.128l-2.562 14.529c-.471 2.675-3.022 4.843-5.697 4.843c-1.337 0-2.452-.542-3.174-1.419");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mmthbxgpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.411 18.128zc2.675 0 4.46 2.168 3.99 4.843l-.556 3.148c-.471 2.675-3.022 4.843-5.697 4.843s-4.46-2.168-3.989-4.843l.555-3.148c.472-2.675 3.022-4.843 5.697-4.843m20.858-5.933c.165-.936-.46-1.695-1.396-1.695s-1.83.759-1.994 1.695s.46 1.695 1.396 1.695s1.829-.759 1.994-1.695m-2.741 5.933l-2.263 12.834M28.737 11.59l-2.989 16.95c-.236 1.338.657 2.422 1.995 2.422h.726");
}

</style>
