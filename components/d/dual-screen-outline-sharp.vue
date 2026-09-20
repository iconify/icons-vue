<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru4lk2pcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dual-screen-outline-sharp" /></template>
<style>
.ru4lk2pcr {
  fill: currentColor;
  d: path("m6 17.6l6 2.4V6.4L6 4zm-2 1.35V2h2l8 3.025V22.95zm8 .05v-2h6V4H6V2h14v17zm-6-1.4V4z");
}

</style>
