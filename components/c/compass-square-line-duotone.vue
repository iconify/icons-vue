<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="od3f1jy1a"/><path class="lxnzn9nmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-square-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.od3f1jy1a {
  d: path("M13.024 14.5602C13.5166 14.3631 13.763 14.2646 13.9562 14.0951C14.0055 14.052 14.0518 14.0056 14.095 13.9563C14.2645 13.7631 14.363 13.5168 14.5601 13.0241C15.484 10.7143 15.946 9.55942 15.4977 8.89976C15.3914 8.74336 15.2565 8.60846 15.1001 8.50218C14.4405 8.05392 13.2856 8.51588 10.9758 9.43979C10.4831 9.63686 10.2368 9.73539 10.0435 9.90486C9.99429 9.94804 9.94792 9.99441 9.90474 10.0437C9.73527 10.2369 9.63673 10.4832 9.43967 10.9759C8.51575 13.2857 8.0538 14.4406 8.50206 15.1002C8.60834 15.2566 8.74324 15.3915 8.89964 15.4978C9.5593 15.9461 10.7142 15.4841 13.024 14.5602Z");
}

</style>
