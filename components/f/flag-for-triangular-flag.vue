<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t9ozyacul"/><path class="j14h1kg1c"/><path class="b-hw3cm6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-triangular-flag" /></template>
<style>
.b-hw3cm6p {
  fill: var(--svg-color--c37029, #c37029);
  d: path("M9.461 62.02V1.68c0-.618.713-1.148 1.739-1.439A6.8 6.8 0 0 0 9.461.009C7.554.009 6 .757 6 1.68v60.34c0 .914 1.554 1.655 3.461 1.655c.636 0 1.236-.079 1.739-.233c-1.026-.275-1.739-.816-1.739-1.422");
}

.j14h1kg1c {
  fill: var(--svg-color--f28f20, #f28f20);
  d: path("M12.926 62.02c0 .914-1.547 1.655-3.465 1.655C7.554 63.675 6 62.934 6 62.02V1.68C6 .757 7.554.009 9.461.009c1.918 0 3.465.748 3.465 1.671z");
}

.t9ozyacul {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("m12.983 42.3l40.21-17.857c2.607-1.158 2.607-4.183 0-5.341L12.983 1.246c-2.637-1.171-6.05.317-6.05 2.671v35.71c0 2.357 3.413 3.844 6.05 2.673");
}

</style>
