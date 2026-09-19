<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o_gjz8qww"/><path class="s3sig6tkv"/><path class="smx0ezbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-lithuania" /></template>
<style>
.o_gjz8qww {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 25h64v14H0z");
}

.s3sig6tkv {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

.smx0ezbgg {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

</style>
