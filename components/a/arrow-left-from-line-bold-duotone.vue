<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqfv9_bht"/><path class="g2z0o6bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-from-line-bold-duotone" /></template>
<style>
.g2z0o6bph {
  fill: currentColor;
  d: path("M16 12.7501L4.93164 12.7501L7.88086 15.4464C8.18649 15.7258 8.20801 16.2002 7.92871 16.506C7.64928 16.8116 7.17485 16.8331 6.86914 16.5538L2.49414 12.5538C2.33874 12.4117 2.25 12.2107 2.25 12.0001C2.25 11.7895 2.33874 11.5885 2.49414 11.4464L6.86914 7.44639C7.17485 7.16709 7.64928 7.18861 7.92871 7.49424C8.20801 7.79995 8.18649 8.27437 7.88086 8.55381L4.93164 11.2501L16 11.2501C16.4142 11.2501 16.75 11.5859 16.75 12.0001C16.75 12.4143 16.4142 12.7501 16 12.7501Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.oqfv9_bht {
  fill: currentColor;
  d: path("M20.25 20C20.25 20.4142 20.5858 20.75 21 20.75C21.4142 20.75 21.75 20.4142 21.75 20L21.75 4C21.75 3.58579 21.4142 3.25 21 3.25C20.5858 3.25 20.25 3.58579 20.25 4L20.25 20Z");
}

</style>
