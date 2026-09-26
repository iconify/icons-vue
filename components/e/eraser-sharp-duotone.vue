<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bk7byacbp"/><path class="wntpr81_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-sharp-duotone" /></template>
<style>
.bk7byacbp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M13.4853 20L23 20L23 22L7.071 22C6.8058 22 6.5514 21.8946 6.3639 21.7071L1.2928 16.6361C1.1053 16.4486 1 16.1942 1 15.929C1 15.6638 1.1053 15.4094 1.2928 15.2219L8 8.5147L16.4853 17L13.4853 20ZM3.4142 15.929L7.4852 20L10.6569 20L13.6569 17L8 11.3431L3.4142 15.929Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wntpr81_j {
  d: path("M8 8.5147L14.2219 2.2928C14.4094 2.1053 14.6638 2 14.929 2C15.1942 2 15.4486 2.1053 15.6361 2.2928L22.7072 9.3639C22.8947 9.5514 23 9.8058 23 10.071C23 10.3362 22.8947 10.5906 22.7072 10.7781L16.4853 17L8 8.5147Z");
}

</style>
