<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ixys9inif"/><path class="d0k502nsw"/><path class="efb3h0bra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balloon-linear" /></template>
<style>
.d0k502nsw {
  d: path("M12.5 6C14.1436 6.01326 15.4867 7.35641 15.5 9");
}

.efb3h0bra {
  d: path("M12 20.3502H12.0001C12.3212 20.3502 12.4818 20.3502 12.5933 20.3283C13.2466 20.1999 13.6441 19.5557 13.4511 18.9384C13.4181 18.833 13.342 18.6962 13.1896 18.4227M12 20.3502C11.6788 20.3502 11.5182 20.3502 11.4067 20.3283C10.7534 20.1999 10.3559 19.5557 10.5489 18.9384C10.5819 18.833 10.658 18.6963 10.8104 18.4227L10.8104 18.4227M12 20.3502V22.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixys9inif {
  d: path("M19.5603 9.80427C19.5937 14.0798 16.142 18.0342 12 17.9997C7.858 17.9652 4.59419 13.9549 4.56077 9.67933C4.52734 5.40377 7.858 1.96572 12 2.00023C16.142 2.03473 19.5268 5.52872 19.5603 9.80427Z");
}

</style>
