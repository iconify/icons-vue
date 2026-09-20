<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d8d3h88an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:database-settings-16-regular" /></template>
<style>
.d8d3h88an {
  fill: currentColor;
  d: path("M10.07 7.746a2 2 0 0 0 2.91.001l.324-.344c.297.14.577.316.835.519l-.126.422a2 2 0 0 0 1.456 2.518l.348.083a4.7 4.7 0 0 1 .011 1.017l-.46.117a2 2 0 0 0-1.431 2.479l.156.556q-.383.294-.822.497l-.337-.357a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.423a2 2 0 0 0-1.456-2.518l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.478l-.156-.557q.382-.294.822-.497zM8 1c2.851 0 5 1.075 5 2.5v2.708a5.5 5.5 0 0 0-1-.185V5.021A7.4 7.4 0 0 1 8 6a7.4 7.4 0 0 1-4-.979V12.5c0 .478.955 1.125 2.541 1.384c.188.39.422.753.692 1.086C4.773 14.796 3 13.794 3 12.5v-9C3 2.075 5.149 1 8 1m3.501 9.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M8 2c-2.442 0-4 .888-4 1.5S5.559 5 8 5s4-.888 4-1.5S10.441 2 8 2");
}

</style>
