<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_c_6bb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-fill" /></template>
<style>
.y_c_6bb6e {
  fill: currentColor;
  d: path("M3.707 4.292A3 3 0 0 1 5 4h14c.448 0 .889.099 1.293.292l-5 5.001C14.98 9.605 14.468 10 14 10h-4c-.468 0-.98-.395-1.293-.707ZM2.292 5.707l5.001 5C8.008 11.422 8.961 12 10 12h4c1.039 0 1.992-.578 2.707-1.293l5.001-5c.193.404.292.845.292 1.293v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293");
}

</style>
