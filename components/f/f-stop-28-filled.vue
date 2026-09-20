<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v9h7ukbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:f-stop-28-filled" /></template>
<style>
.v9h7ukbke {
  fill: currentColor;
  d: path("M15.598 7.987a4 4 0 0 1 5.33-2.977l.471.176a1 1 0 1 0 .702-1.872l-.47-.177c-3.473-1.302-7.284.826-7.996 4.466L12.775 12H7.75a1 1 0 1 0 0 2h4.633l-.98 5.013a4 4 0 0 1-5.33 2.977l-.472-.176a1 1 0 1 0-.702 1.872l.471.177c3.473 1.302 7.283-.826 7.995-4.466L14.421 14h4.829a1 1 0 1 0 0-2h-4.437z");
}

</style>
