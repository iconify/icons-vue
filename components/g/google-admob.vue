<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ybruk1-ml"/><path class="h1llb47se"/><path class="whwh2vh_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-admob" /></template>
<style>
.h1llb47se {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M256 223.949c0 17.613-14.336 31.949-31.949 31.949s-31.949-14.336-31.949-31.95c0-17.612 14.336-31.948 31.95-31.948C241.663 192 256 206.336 256 223.949");
}

.whwh2vh_y {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M124.006 254.874c18.125.204 32.973-14.234 33.178-32.359v-.205c-.512-17.612-15.258-31.539-32.87-31.027h-.717c-34.919-2.662-61.235-32.973-58.778-67.993v-.512C67.38 91.238 92.467 66.355 124.006 64c17.613.717 32.461-13.005 33.178-30.618v-.512C156.979 14.746 142.131.102 124.006.305h-2.252C53.862 3.482.41 59.187 0 127.181v.512c0 79.77 69.94 127.283 122.06 127.283h1.946z");
}

.ybruk1-ml {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("M122.163.41C125.85.102 129.433 0 133.12 0C199.782 2.458 253.338 55.91 256 122.573v100.659c-.102 18.227-14.95 32.87-33.075 32.769c-16.589-2.561-29.287-16.078-30.823-32.769v-100.66c-2.764-35.122-33.484-61.44-68.608-58.674c-.41 0-.819.102-1.228.102");
}

</style>
