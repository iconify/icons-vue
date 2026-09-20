<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="te7w0ccll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-20-regular" /></template>
<style>
.te7w0ccll {
  fill: currentColor;
  d: path("M3.133 9.16a.5.5 0 1 0 .738.675l5.631-6.168v13.831a.5.5 0 1 0 1 0V3.67l5.628 6.165a.5.5 0 0 0 .739-.674l-6.314-6.916a.75.75 0 0 0-.632-.24a.75.75 0 0 0-.476.24z");
}

</style>
