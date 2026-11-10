<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x94gylniq"/><path clip-rule="evenodd" class="yhu_rjy5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-compact-four-directions-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x94gylniq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.832 11.44C23.056 11.77 23.056 12.21 22.832 12.55L20.535 15.99L18.871 14.88L20.798 11.99L18.871 9.1L20.535 7.99L22.832 11.44Z");
}

.yhu_rjy5g {
  fill-rule: evenodd;
  d: path("M16 20.53L12.555 22.83C12.219 23.06 11.781 23.06 11.445 22.83L8 20.53L9.109 18.87L12 20.8L14.891 18.87L16 20.53ZM5.129 9.1L3.201 11.99L5.129 14.88L3.465 15.99L1.168 12.55C0.944 12.21 0.944 11.77 1.168 11.44L3.465 7.99L5.129 9.1ZM11.507 1.11C11.821 0.96 12.261 0.95 12.555 1.15L16 3.45L14.891 5.11L12 3.18L9.109 5.11L8 3.45L11.507 1.11Z");
}

</style>
