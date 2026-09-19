<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aimndkzko"/><path class="sf67-2b5j"/><path class="ytd8s1bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-bahamas" /></template>
<style>
.aimndkzko {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M1 25h63v14H1z");
}

.sf67-2b5j {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M32.416 32L4.486 11.5C1.513 13.407 0 16.942 0 21v22c0 3.883 1.385 7.289 4.11 9.246l28.344-20.219z");
}

.ytd8s1bfc {
  fill: var(--svg-color--00abc9, #00abc9);
  d: path("M22.68 39L4.121 52.238C5.656 53.345 7.609 54 10 54h44c6.627 0 10-4.925 10-11v-4zM54 10H10c-2.201 0-4.03.553-5.514 1.5L22.879 25h41.12v-4c0-6.075-3.373-11-10-11");
}

</style>
