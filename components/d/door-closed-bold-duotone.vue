<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff_-gvaty"/><path class="f5hhf-bls"/><path class="amslx3b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:door-closed-bold-duotone" /></template>
<style>
.amslx3b-g {
  fill: currentColor;
  d: path("M15.5 11.65C15.9693 11.65 16.3504 12.0304 16.3506 12.4996C16.3506 12.969 15.9694 13.3502 15.5 13.3502C15.0308 13.35 14.6504 12.9689 14.6504 12.4996C14.6506 12.0305 15.0309 11.6502 15.5 11.65Z");
}

.f5hhf-bls {
  fill: currentColor;
  d: path("M22 21.2496C22.4141 21.2496 22.7498 21.5856 22.75 21.9996C22.75 22.4138 22.4142 22.7496 22 22.7496H2C1.58579 22.7496 1.25 22.4138 1.25 21.9996C1.2502 21.5856 1.58591 21.2496 2 21.2496H22Z");
}

.ff_-gvaty {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 22V6C5 4.1144 5 3.1716 5.5858 2.5858C6.1716 2 7.1144 2 9 2H15C16.8856 2 17.8284 2 18.4142 2.5858C19 3.1716 19 4.1144 19 6V22H5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
