<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="evxcoq2mj"/><path class="kcw4gpn5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:activity-sparkles-sharp" /></template>
<style>
.evxcoq2mj {
  d: path("M1 12L5 12L8 4L16 20L18.4933 13.3511");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kcw4gpn5l {
  fill: currentColor;
  d: path("M19.5492 3.3739L20.4196 5.5804L22.6261 6.4508C22.8518 6.5397 23 6.7576 23 7C23 7.2424 22.8518 7.4603 22.6261 7.5492L20.4196 8.4196L19.5492 10.6261C19.4603 10.8518 19.2424 11 19 11C18.7576 11 18.5397 10.8518 18.4508 10.6261L17.5804 8.4196L15.3739 7.5492C15.1482 7.4603 15 7.2424 15 7C15 6.7576 15.1482 6.5397 15.3739 6.4508L17.5804 5.5804L18.4508 3.3739C18.5397 3.1482 18.7576 3 19 3C19.2424 3 19.4603 3.1482 19.5492 3.3739ZM4.8433 15.2337L5.3873 16.6127L6.7663 17.1567C6.9074 17.2123 7 17.3485 7 17.5C7 17.6515 6.9074 17.7877 6.7663 17.8433L5.3873 18.3873L4.8433 19.7663C4.7877 19.9074 4.6515 20 4.5 20C4.3485 20 4.2123 19.9074 4.1567 19.7663L3.6127 18.3873L2.2337 17.8433C2.0926 17.7877 2 17.6515 2 17.5C2 17.3485 2.0926 17.2123 2.2337 17.1567L3.6127 16.6127L4.1567 15.2337C4.2123 15.0926 4.3485 15 4.5 15C4.6515 15 4.7877 15.0926 4.8433 15.2337Z");
  stroke: none;
}

</style>
