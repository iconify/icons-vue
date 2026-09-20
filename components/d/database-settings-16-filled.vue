<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wnyiaebcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:database-settings-16-filled" /></template>
<style>
.wnyiaebcn {
  fill: currentColor;
  d: path("M10.07 7.746a2 2 0 0 0 2.91.001l.324-.344c.297.14.577.316.835.519l-.126.422a2 2 0 0 0 1.456 2.518l.348.083a4.7 4.7 0 0 1 .011 1.017l-.46.117a2 2 0 0 0-1.431 2.479l.156.556q-.383.294-.822.497l-.337-.357a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.423a2 2 0 0 0-1.456-2.518l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.478l-.156-.557q.382-.294.822-.497zM3 5.487C4.057 6.413 5.864 7 8 7q.175 0 .348-.007A5.5 5.5 0 0 0 6 11.5c0 1.316.463 2.523 1.233 3.47C4.773 14.796 3 13.794 3 12.5zm8.501 5.013a1 1 0 1 0 0 2a1 1 0 0 0 0-2M8 1c2.761 0 5 1.12 5 2.5S10.761 6 8 6S3 4.88 3 3.5S5.239 1 8 1");
}

</style>
