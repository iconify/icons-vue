<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmxtikbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-keys-sharp" /></template>
<style>
.kmxtikbee {
  fill: currentColor;
  d: path("M7.23 16.77v-1.54h9.54v1.54zm-4-4v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm-16-4V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54z");
}

</style>
