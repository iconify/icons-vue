<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nljc8nbdc"/><path class="r0p_zqv_y"/><path class="vcpzcubba"/><path class="erjx3v97p"/><path class="ib-1vfjvj"/><path class="unmhjsbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-range-bold-duotone" /></template>
<style>
.erjx3v97p {
  fill: currentColor;
  d: path("M17 16C17.4142 16 17.75 16.3358 17.75 16.75C17.75 17.1642 17.4142 17.5 17 17.5H12C11.5858 17.5 11.25 17.1642 11.25 16.75C11.25 16.3358 11.5858 16 12 16H17Z");
}

.ib-1vfjvj {
  fill: currentColor;
  d: path("M12 12C12.4142 12 12.75 12.3358 12.75 12.75C12.75 13.1642 12.4142 13.5 12 13.5H7C6.58579 13.5 6.25 13.1642 6.25 12.75C6.25 12.3358 6.58579 12 7 12H12Z");
}

.nljc8nbdc {
  fill: currentColor;
  d: path("M2 11.75C2 7.97876 2 6.09315 3.17157 4.92157C4.34315 3.75 6.22876 3.75 10 3.75H14C17.7712 3.75 19.6569 3.75 20.8284 4.92157C22 6.09315 22 7.97876 22 11.75V13.75C22 17.5212 22 19.4069 20.8284 20.5784C19.6569 21.75 17.7712 21.75 14 21.75H10C6.22876 21.75 4.34315 21.75 3.17157 20.5784C2 19.4069 2 17.5212 2 13.75V11.75Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r0p_zqv_y {
  fill: currentColor;
  d: path("M17 2.25C17.4142 2.25 17.75 2.58579 17.75 3V3.83008C19.1894 3.94533 20.1349 4.22766 20.8291 4.92188C21.637 5.73003 21.8871 6.87801 21.9648 8.75H2.03516C2.11291 6.87777 2.36378 5.73004 3.17188 4.92188C3.86603 4.22772 4.81081 3.94535 6.25 3.83008V3C6.25 2.58579 6.58579 2.25 7 2.25C7.41421 2.25 7.75 2.58579 7.75 3V3.76465C8.41527 3.75174 9.16095 3.75 10 3.75H14C14.839 3.75 15.5848 3.75175 16.25 3.76465V3C16.25 2.58579 16.5858 2.25 17 2.25Z");
}

.unmhjsbpe {
  fill: currentColor;
  d: path("M17 12C17.4142 12.0001 17.75 12.3358 17.75 12.75C17.75 13.1642 17.4142 13.4999 17 13.5C16.5858 13.5 16.25 13.1642 16.25 12.75C16.25 12.3358 16.5858 12 17 12Z");
}

.vcpzcubba {
  fill: currentColor;
  d: path("M7 16C7.41421 16 7.75 16.3358 7.75 16.75C7.75 17.1642 7.41421 17.5 7 17.5C6.58579 17.5 6.25 17.1642 6.25 16.75C6.25 16.3358 6.58579 16 7 16Z");
}

</style>
