<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgwf1zbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-wash" /></template>
<style>
.zgwf1zbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15H18M6 15C4.8954 15 4 15.895 4 17V20C4 21.105 4.8954 22 6 22C7.1046 22 8 21.105 8 20H16C16 21.105 16.8954 22 18 22C19.1046 22 20 21.105 20 20V17C20 15.895 19.1046 15 18 15M6 15L7.1807 12.219C7.4943 11.48 8.2191 11 9.0217 11H14.9783C15.7809 11 16.5057 11.48 16.8193 12.219L18 15M6.4245 14H4.5M17.5755 14H19.5M9.6 3.8C9.8596 4.146 10 4.567 10 5C10 6.105 9.1046 7 8 7C6.8954 7 6 6.105 6 5C6 4.567 6.1404 4.146 6.4 3.8L7.6 2.2C7.6944 2.074 7.8426 2 8 2C8.1574 2 8.3056 2.074 8.4 2.2L9.6 3.8ZM17.6 3.8C17.8596 4.146 18 4.567 18 5C18 6.105 17.1046 7 16 7C14.8954 7 14 6.105 14 5C14 4.567 14.1404 4.146 14.4 3.8L15.6 2.2C15.6944 2.074 15.8426 2 16 2C16.1574 2 16.3056 2.074 16.4 2.2L17.6 3.8Z");
}

</style>
