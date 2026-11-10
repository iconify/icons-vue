<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rf7-znb2y"/><path class="cs5y0bcjy"/><path clip-rule="evenodd" class="yxc_zrblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baggage-claim-duotone" /></template>
<style>
.cs5y0bcjy {
  d: path("M6 17C7.6568 17 9 18.343 9 20C9 21.657 7.6568 23 6 23C4.3432 23 3 21.657 3 20C3 18.343 4.3432 17 6 17ZM18 17C19.6569 17 21 18.343 21 20C21 21.657 19.6569 23 18 23C16.3431 23 15 21.657 15 20C15 18.343 16.3431 17 18 17Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rf7-znb2y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C12.5523 1 13 1.448 13 2V2.881C13 2.981 13.0752 3.066 13.1748 3.079C17.59 3.655 21 7.428 21 12V15.8C21 15.91 21.0897 16 21.2002 16H22C22.5523 16 23 16.448 23 17C23 17.552 22.5523 18 22 18H2C1.4477 18 1 17.552 1 17C1 16.448 1.4477 16 2 16H2.7998C2.9103 16 3 15.91 3 15.8V12C3 7.428 6.41 3.655 10.8252 3.079C10.9248 3.066 11 2.981 11 2.881V2C11 1.448 11.4477 1 12 1Z");
}

.yxc_zrblg {
  fill-rule: evenodd;
  d: path("M13.5 7C14.3283 7 15 7.672 15 8.5V10.8C15 10.91 15.0897 11 15.2002 11H15.5C16.3284 11 17 11.672 17 12.5V15.8C17 15.91 16.9103 16 16.7998 16H7.2002C7.0897 16 7 15.91 7 15.8V12.5C7 11.672 7.6715 11 8.5 11H8.7998C8.9103 11 9 10.91 9 10.8V8.5C9 7.672 9.6717 7 10.5 7H13.5ZM11.2002 9C11.0897 9 11 9.09 11 9.2V10.8C11 10.91 11.0897 11 11.2002 11H12.7998C12.9103 11 13 10.91 13 10.8V9.2C13 9.09 12.9103 9 12.7998 9H11.2002Z");
}

</style>
