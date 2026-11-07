<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i26vi13vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-help-fill" /></template>
<style>
.i26vi13vb {
  fill: currentColor;
  d: path("M15.236 3.832A3 3 0 1 1 18 8a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 17 5a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M13.432 10H10c-.468 0-.98-.395-1.293-.707l-5-5.001A3 3 0 0 1 5 4h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779A6 6 0 0 0 13.432 10M2.292 5.707l5.001 5C8.008 11.422 8.961 12 10 12h4c.521 0 1.032-.151 1.493-.389c1.033.554 2.21.887 3.388.845a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293M18.01 9a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
