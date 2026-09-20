<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe88lacbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-microphone-below-16-filled" /></template>
<style>
.fe88lacbq {
  fill: currentColor;
  d: path("M14 12.5c0 .477-.268.866-.606 1.157c-.341.293-.805.534-1.334.727C10.996 14.77 9.56 15 8 15s-2.997-.23-4.06-.616c-.529-.193-.993-.434-1.334-.727C2.267 13.366 2 12.977 2 12.5v-1.158c.344.284.753.53 1.194.733C4.45 12.655 6.15 13 8 13s3.55-.345 4.806-.925c.44-.203.85-.449 1.194-.733zm-1.613-4.667c1.062.49 1.545 1.068 1.605 1.562q.006.052.008.105c0 .516-.474 1.141-1.613 1.667C11.29 11.673 9.739 12 8 12c-1.74 0-3.29-.327-4.387-.833C2.474 10.641 2 10.016 2 9.5q.001-.053.007-.105c.06-.494.544-1.072 1.606-1.562C4.71 7.327 6.266 7 8 7c1.735 0 3.29.327 4.387.833m-.497-4.444a.5.5 0 0 1 .707.707a6.5 6.5 0 0 1-9.193 0a.5.5 0 1 1 .707-.707a5.5 5.5 0 0 0 7.779 0M10.12 1.62a.5.5 0 0 1 .707.707a4 4 0 0 1-5.657 0a.5.5 0 1 1 .707-.707a3 3 0 0 0 4.243 0");
}

</style>
