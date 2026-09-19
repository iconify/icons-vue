<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_4aebsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-panorama-wide-angle-select" /></template>
<style>
.ow_4aebsw {
  fill: currentColor;
  d: path("M12 4c-2.73 0-5.22.24-7.95.72l-.93.16l-.25.9C2.29 7.85 2 9.93 2 12s.29 4.15.87 6.22l.25.89l.93.16c2.73.49 5.22.73 7.95.73s5.22-.24 7.95-.72l.93-.16l.25-.89c.58-2.08.87-4.16.87-6.23s-.29-4.15-.87-6.22l-.25-.89l-.93-.16C17.22 4.24 14.73 4 12 4");
}

</style>
