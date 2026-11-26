<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l2y8acc_a"/><path class="lysishqwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:champagne-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l2y8acc_a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 15.9104C9.6959 15.673 8.5483 14.9757 7.687 13.9588C6.6161 12.6947 6 10.9575 6 9C6 8.9517 6.0035 8.9035 6.0105 8.8557C6.3544 6.4976 6.7542 4.148 7.2096 1.8089C7.3011 1.3391 7.7126 1 8.1912 1L15.8088 1C16.2874 1 16.6989 1.3391 16.7904 1.8089C17.2458 4.148 17.6456 6.4976 17.9895 8.8557C17.9965 8.9035 18 8.9517 18 9C18 10.9575 17.3839 12.6947 16.313 13.9588C15.4517 14.9757 14.3041 15.673 13 15.9104L13 21L16 21L17 21L17 23L16 23L8 23L7 23L7 21L8 21L11 21Z");
}

.lysishqwh {
  d: path("M12 5.0004L7.4686 5.0004C6.9797 5.0004 6.5625 5.3538 6.4822 5.8361C6.3148 6.8409 6.1575 7.8474 6.0105 8.8557C6.0035 8.9035 6 8.9517 6 9C6 10.9575 6.6161 12.6947 7.687 13.9588C8.7625 15.2286 10.2844 16 12 16C13.7156 16 15.2375 15.2286 16.313 13.9588C17.3839 12.6947 18 10.9575 18 9C18 8.9517 17.9965 8.9035 17.9895 8.8557C17.8425 7.8474 17.6852 6.8409 17.5178 5.8361C17.4375 5.3538 17.0203 5.0004 16.5314 5.0004Z");
}

</style>
