<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqtr336sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-horizontal-fill" /></template>
<style>
.xqtr336sp {
  fill: currentColor;
  d: path("M8 5C9.6569 5 11 6.343 11 8V20C11 21.657 9.6568 23 8 23H6C4.3432 23 3 21.657 3 20V8C3 6.343 4.3431 5 6 5H8ZM18 5C19.6569 5 21 6.343 21 8V12C21 13.657 19.6569 15 18 15H16C14.3431 15 13 13.657 13 12V8C13 6.343 14.3431 5 16 5H18ZM22 1C22.552 1 23 1.448 23 2C23 2.552 22.552 3 22 3H2C1.4477 3 1 2.552 1 2C1 1.448 1.4477 1 2 1H22Z");
}

</style>
