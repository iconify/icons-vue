<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ge0wh-0qw"/><path class="e2a5o8qra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-sharp-two-tone" /></template>
<style>
.e2a5o8qra {
  d: path("M9.5 3C9.5 4 9.769 5.308 8.5 7C7 9 7 11 7 12.5L7 19C7 19.7993 7.552 21.4572 9.7149 21.9443C9.9029 21.9867 10.0969 22 10.2897 22L13.7103 22C13.9031 22 14.0971 21.9867 14.2851 21.9443C16.448 21.4572 17 19.7993 17 19L17 12.5C17 11 17 9 15.5 7C14.231 5.308 14.5 4 14.5 3ZM9.5 3L8.5 3L8.5 2L15.5 2L15.5 3L14.5 3M7 14.2764C7.48139 14.2764 7.94988 14.4033 8.33498 14.6382C8.72008 14.8731 9.18857 15 9.66997 15C10.1514 15 10.6199 14.8731 11.0049 14.6382C11.39 14.4033 11.8585 14.2764 12.3399 14.2764C12.8213 14.2764 13.2898 14.4033 13.6749 14.6382C14.06 14.8731 14.5285 15 15.0099 15C15.8526 15 16.6231 14.6129 17 14");
}

.ge0wh-0qw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.5 3C8.5 4.1139 8.7273 5.0303 7.7 6.4C5.9851 8.6865 6 10.9905 6 12.5L6 19C6 20.1656 6.7841 22.3093 9.4952 22.9199L9.4949 22.9198C9.7804 22.9842 10.0543 23 10.2897 23L13.7103 23C13.9457 23 14.2196 22.9842 14.5051 22.9198L14.5048 22.9199C17.2159 22.3093 18 20.1656 18 19L18 12.5C18 10.9905 18.0149 8.6865 16.3 6.4C15.2727 5.0303 15.5 4.1139 15.5 3C15.5 2.4477 15.0523 2 14.5 2L9.5 2C8.9477 2 8.5 2.4477 8.5 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
