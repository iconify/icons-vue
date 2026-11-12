<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5qydhb7a"/><path class="ocquu9v9w"/><path class="t6vjqsiao"/><path class="z_rtvxmtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-bold-duotone" /></template>
<style>
.ocquu9v9w {
  fill: currentColor;
  d: path("M15.5 7.25C15.9142 7.25 16.25 7.58579 16.25 8C16.25 8.41421 15.9142 8.75 15.5 8.75H8.5C8.08579 8.75 7.75 8.41421 7.75 8C7.75 7.58579 8.08579 7.25 8.5 7.25H15.5Z");
}

.s5qydhb7a {
  fill: currentColor;
  d: path("M15.5 12.25C15.9142 12.25 16.25 12.5858 16.25 13C16.25 13.4142 15.9142 13.75 15.5 13.75H8.5C8.08579 13.75 7.75 13.4142 7.75 13C7.75 12.5858 8.08579 12.25 8.5 12.25H15.5Z");
}

.t6vjqsiao {
  fill: currentColor;
  d: path("M22 1.25C22.4142 1.25 22.75 1.58579 22.75 2C22.75 2.41421 22.4142 2.75 22 2.75H2C1.58579 2.75 1.25 2.41421 1.25 2C1.25 1.58579 1.58579 1.25 2 1.25H22Z");
}

.z_rtvxmtm {
  fill: currentColor;
  d: path("M4 2.75V12.2774C4 13.6175 4 14.2875 4.2681 14.8783C4.5362 15.4692 5.04046 15.9104 6.04896 16.7928L8.04897 18.5429C9.93152 20.1901 10.8728 21.0137 12 21.0137C13.1272 21.0137 14.0685 20.1901 15.951 18.5429L17.951 16.7929C18.9595 15.9104 19.4638 15.4692 19.7319 14.8783C20 14.2875 20 13.6175 20 12.2774V2.75H4Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
