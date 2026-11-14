<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjr1erb2s"/><path class="ih1_hub3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:apple-bold-duotone" /></template>
<style>
.ih1_hub3u {
  fill: currentColor;
  d: path("M14.0234 1.42094C14.3432 1.15781 14.8158 1.20381 15.0791 1.52348C15.3422 1.84322 15.2962 2.3159 14.9766 2.57915C13.5971 3.71527 12.8944 5.1213 12.7715 6.69243C12.5094 6.85038 12.2515 7.02061 12 7.20024C11.7605 7.02919 11.5148 6.86736 11.2656 6.71587C11.388 4.6847 12.2871 2.85087 14.0234 1.42094Z");
}

.zjr1erb2s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 7.2C10.6 6.2 9 5.5 7.6 5.5C4.6 5.5 3 8.3 3 11.6C3 16.6 6 22 9 22C10.3 22 11 21.3 12 21.3C13 21.3 13.7 22 15 22C18 22 21 16.6 21 11.6C21 8.3 19.4 5.5 16.4 5.5C15 5.5 13.4 6.2 12 7.2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
