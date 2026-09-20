<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oc2fitb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:database-settings-20-filled" /></template>
<style>
.oc2fitb5j {
  fill: currentColor;
  d: path("M13.07 10.746a2 2 0 0 0 2.91.001l.324-.344c.298.14.577.316.835.519l-.126.422a2 2 0 0 0 1.456 2.518l.348.083a4.7 4.7 0 0 1 .011 1.017l-.46.117a2 2 0 0 0-1.431 2.479l.156.556q-.382.294-.823.497l-.336-.357a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.423a2 2 0 0 0-1.456-2.518l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.478l-.156-.557q.383-.293.822-.497zM4 7.12c.383.362.841.66 1.31.896C6.563 8.64 8.223 9 10 9c.848 0 1.668-.083 2.43-.236c-1.928.983-3.313 3.235-3.423 5.45Q9 14.357 9 14.5c0 1.328.47 2.546 1.254 3.496Q10.128 18 10 18c-3.314 0-6-1.343-6-3zm10.501 6.38a1 1 0 1 0 0 2a1 1 0 0 0 0-2M10 2c3.314 0 6 1.343 6 3s-2.686 3-6 3s-6-1.343-6-3s2.686-3 6-3");
}

</style>
