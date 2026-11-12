<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ol_17ac7k"/><path class="nw_pr2p7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-grab-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nw_pr2p7g {
  d: path("M11.9626 22.0001C7.82536 22.0181 4.48426 19.0501 4.50006 15.3691V10.3551C4.50006 9.3203 5.33884 8.48145 6.37361 8.48145C7.40839 8.48145 8.24725 9.32039 8.24725 10.3552L8.24742 13.6827");
}

.ol_17ac7k {
  d: path("M8.24725 10.3552C8.24725 9.32039 7.40839 8.48145 6.37361 8.48145C5.33884 8.48145 4.50006 9.3203 4.50006 10.3551V15.3691C4.48426 19.0501 7.82536 22.0181 11.9626 22.0001C16.0998 21.9821 19.4664 18.9831 19.4822 15.3031V10.338C19.4822 9.30321 18.6502 8.46445 17.6154 8.46445C16.5806 8.46445 15.7418 9.3033 15.7418 10.3381M11.9945 10.1679L11.9945 8.66269C11.9945 7.62791 12.8333 6.78915 13.8681 6.78915C14.9029 6.78915 15.7417 7.62791 15.7417 8.66268V11.1649M11.9945 8.66269L11.9945 8.48154C11.9945 7.44676 11.1557 6.60791 10.1209 6.60791C9.0861 6.60791 8.24725 7.44676 8.24725 8.48154L8.24744 13.6827");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
