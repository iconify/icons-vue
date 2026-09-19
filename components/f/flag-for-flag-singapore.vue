<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tk3b7rprs"/><path class="erqlizbco"/><path class="rr0ikrbjd"/><path class="grxq6ubfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-singapore" /></template>
<style>
.erqlizbco {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 22c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11v11H0z");
}

.grxq6ubfg {
  fill: var(--svg-color--fff, #fff);
  d: path("m21.93 16.752l-1.543.002l-.48-1.562l-.475 1.562l-1.546-.002l1.254.951l-.488 1.552l1.257-.964l1.261.964l-.489-1.552zm4.408 3.278h-1.543l-.48-1.563l-.475 1.563h-1.546l1.252.948l-.486 1.551l1.257-.964l1.258.964l-.485-1.551zm-1.65 5.24H23.14l-.475-1.563l-.475 1.563h-1.546l1.252.95l-.486 1.55l1.257-.964l1.258.964l-.487-1.55zm-5.528 0h-1.539l-.481-1.563l-.474 1.563H15.12l1.252.95l-.485 1.55l1.253-.964l1.261.964l-.486-1.55zm-1.646-5.24h-1.543l-.48-1.563l-.471 1.563h-1.55l1.252.948l-.486 1.551l1.257-.964l1.258.964l-.486-1.551z");
}

.rr0ikrbjd {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.826 22.12a7.82 7.82 0 0 1 7.498-7.814A8.277 8.277 0 0 0 7.315 22.12a8.277 8.277 0 0 0 8.277 8.279c.957 0 1.878-.161 2.732-.462a7.82 7.82 0 0 1-7.498-7.817");
}

.tk3b7rprs {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 55H10C3.373 55 0 50.075 0 44V33h64v11c0 6.075-3.373 11-10 11");
}

</style>
