<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnn_fofpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-settings-20-filled" /></template>
<style>
.xnn_fofpu {
  fill: currentColor;
  d: path("M13.07 10.746a2 2 0 0 0 2.91.001l.324-.344c.298.14.577.316.835.519l-.126.422a2 2 0 0 0 1.456 2.518l.348.083a4.7 4.7 0 0 1 .011 1.017l-.46.117a2 2 0 0 0-1.431 2.479l.156.556q-.382.294-.823.497l-.336-.357a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.423a2 2 0 0 0-1.456-2.518l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.478l-.156-.557q.383-.293.822-.497zM9.022 15q.047.517.185 1H2.5a.5.5 0 0 1 0-1zm5.478-1.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M15 5a2 2 0 0 1 2 2v2.6A5.5 5.5 0 0 0 9.023 14H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2z");
}

</style>
