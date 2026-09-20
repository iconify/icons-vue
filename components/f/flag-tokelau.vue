<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yxis8ospw"/><path class="rsp4iubrt"/><path class="oca--zbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-tokelau" /></template>
<style>
.oca--zbbk {
  fill: var(--svg-color--fed100, #fed100);
  d: path("M32 29H5s-.266-.172-.266-.5S5 28 5 28h27l1.484.5zM5 27s5-2 11-8S26 9 28 8c-1.753 1.753-3.771 14 1.229 18c0 0 2.771.521 2.771 1z");
}

.rsp4iubrt {
  fill: var(--svg-color--fff, #fff);
  d: path("m3.354 11.146l.342 1.102l1.154-.008l-.943.665L4.271 14l-.924-.69l-.928.684l.371-1.092l-.938-.671l1.153.015zM8.101 18l.44 1.417l1.483-.01l-1.212.857l.469 1.407l-1.189-.887l-1.195.879l.477-1.404l-1.207-.864l1.484.019zm.186-11.481l.342 1.101l1.153-.008l-.942.666l.364 1.095l-.924-.69l-.928.684l.37-1.093l-.938-.671l1.154.015zm4.777 4.401l.242.78l.816-.006l-.667.471l.258.775l-.654-.488l-.658.484l.263-.773l-.664-.475l.816.01z");
}

.yxis8ospw {
  fill: var(--svg-color--00247d, #00247d);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
