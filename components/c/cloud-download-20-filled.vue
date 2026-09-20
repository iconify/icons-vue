<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o99va7b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-download-20-filled" /></template>
<style>
.o99va7b3o {
  fill: currentColor;
  d: path("M10 2c2.817 0 4.415 1.923 4.647 4.246h.07C16.532 6.246 18 7.758 18 9.623q0 .143-.011.283A5.75 5.75 0 0 0 7.772 13h-2.49C3.469 13 2 11.488 2 9.623s1.47-3.377 3.282-3.377h.071C5.587 3.908 7.183 2 10 2m3.5 16a4.5 4.5 0 1 1 0-9a4.5 4.5 0 0 1 0 9m1.602-4.898L14 14.204V11.5a.5.5 0 0 0-1 0v2.704l-1.102-1.102a.562.562 0 1 0-.796.796l2 2c.22.22.576.22.796 0l2-2a.562.562 0 1 0-.796-.796");
}

</style>
