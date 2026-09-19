<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k0v45_bpu"/><path class="dykrr8viu"/><path class="fg4xxj7ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-samoa" /></template>
<style>
.dykrr8viu {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M22 10H10C3.373 10 0 14.925 0 21v11h22z");
}

.fg4xxj7ny {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M12.891 13.878h-1.568l-.484-1.585l-.484 1.585H8.787l1.273.965l-.494 1.573l1.275-.978l1.279.978l-.496-1.573zm-5.912 4.74H5.413l-.487-1.588l-.482 1.588H2.878l1.268.964l-.491 1.578l1.275-.98l1.276.98l-.495-1.578zm11.966-.83l-1.566.002l-.487-1.586l-.484 1.586l-1.568-.002l1.27.967l-.491 1.574l1.275-.98l1.276.98l-.493-1.574zm-3.768 4.469l-1.027.002l-.313-1.039l-.317 1.039l-1.022-.002l.829.63l-.327 1.03l.837-.64l.834.64l-.321-1.03zm-1.745 4.504l-1.929.004l-.597-1.952l-.594 1.952l-1.931-.004l1.562 1.185l-.604 1.941l1.569-1.204l1.571 1.204l-.607-1.941z");
}

.k0v45_bpu {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H22v22H0v11c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

</style>
