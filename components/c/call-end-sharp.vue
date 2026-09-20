<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j12w7c67j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-end-sharp" /></template>
<style>
.j12w7c67j {
  fill: currentColor;
  d: path("m4.064 16.366l-2.972-2.91l.635-.66q2.137-2.148 4.857-3.222T12 8.5t5.404 1.074t4.85 3.222l.654.66l-2.971 2.91l-3.437-2.597v-3.465q-1.142-.396-2.277-.6T12 9.5t-2.223.204t-2.277.6v3.465z");
}

</style>
