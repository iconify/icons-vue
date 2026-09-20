<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zknf17soz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:float-portrait-2-rounded" /></template>
<style>
.zknf17soz {
  fill: currentColor;
  d: path("M9.192 11.385h4.385q.348 0 .578-.23t.23-.578V7.192q0-.348-.23-.577q-.23-.23-.578-.23H9.192q-.348 0-.578.23t-.23.577v3.385q0 .348.23.578t.578.23m9.808 8q0 .69-.462 1.152T17.384 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616z");
}

</style>
