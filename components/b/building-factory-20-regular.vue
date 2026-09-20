<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jwgt--bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-factory-20-regular" /></template>
<style>
.jwgt--bjn {
  fill: currentColor;
  d: path("M4.435 2a1.5 1.5 0 0 0-1.497 1.4l-.866 13A1.5 1.5 0 0 0 3.568 18h2.863a1.5 1.5 0 0 0 1.496-1.6l-.866-13A1.5 1.5 0 0 0 5.564 2zm-.499 1.467a.5.5 0 0 1 .5-.467h1.128a.5.5 0 0 1 .499.467l.867 13a.5.5 0 0 1-.5.533H3.569a.5.5 0 0 1-.498-.533zM16.5 18H8.43a2.5 2.5 0 0 0 .45-1H10v-4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4h.5a.5.5 0 0 0 .5-.5V6.623l-4.166 3.749a.5.5 0 0 1-.835-.372V6.623l-3.51 3.16l-.085-1.27l3.761-3.385A.5.5 0 0 1 13 5.5v3.377l4.165-3.749A.5.5 0 0 1 18 5.5v11a1.5 1.5 0 0 1-1.5 1.5M11 17h4v-4h-4z");
}

</style>
