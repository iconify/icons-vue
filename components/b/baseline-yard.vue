<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lctfee79a"/><circle class="xm4mytbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-yard" /></template>
<style>
.lctfee79a {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2M8 8.22a1.562 1.562 0 0 1 2.45-1.28l-.01-.12c0-.86.7-1.56 1.56-1.56s1.56.7 1.56 1.56l-.01.12A1.562 1.562 0 0 1 16 8.22c0 .62-.37 1.16-.89 1.4c.52.25.89.79.89 1.41c0 .86-.7 1.56-1.56 1.56c-.33 0-.64-.11-.89-.28l.01.12c0 .86-.7 1.56-1.56 1.56s-1.56-.7-1.56-1.56l.01-.12A1.562 1.562 0 0 1 8 11.03c0-.62.37-1.16.89-1.4C8.37 9.38 8 8.84 8 8.22M12 19c-3.31 0-6-2.69-6-6c3.31 0 6 2.69 6 6c0-3.31 2.69-6 6-6c0 3.31-2.69 6-6 6");
}

.xm4mytbxk {
  cx: 12px;
  cy: 9.62px;
  r: 1.56px;
  fill: currentColor;
}

</style>
