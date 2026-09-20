<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7jtplb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heap-snapshot-large-rounded" /></template>
<style>
.z7jtplb0z {
  fill: currentColor;
  d: path("M14.498 18q.416 0 .709-.291t.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293m-5.035-.475q.207 0 .34-.14l5.1-5.1q.141-.134.141-.342q0-.207-.14-.347t-.348-.14t-.34.14l-5.12 5.12q-.14.14-.13.334q.009.194.15.335q.14.14.347.14M9.498 13q.416 0 .709-.291t.293-.707t-.291-.709T9.502 11t-.709.291t-.293.707t.291.709t.707.293m-2.882 8q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zM18 8l-4-4v2.962q0 .44.299.739t.74.299z");
}

</style>
