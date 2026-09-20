<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnifnja8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-24-regular" /></template>
<style>
.cnifnja8l {
  fill: currentColor;
  d: path("M15.757 4.5c.346 0 .666.185.839.485l3.823 6.64a.75.75 0 0 1 0 .75l-3.886 6.75a.75.75 0 0 1-.65.375H12.5a.75.75 0 0 0 0 1.5h3.383a2.25 2.25 0 0 0 1.95-1.127l3.886-6.75c.4-.695.4-1.55 0-2.246l-3.823-6.64a2.469 2.469 0 0 0-4.491.483L8.912 18.84a.948.948 0 0 1-1.736.166L3.56 12.379a.75.75 0 0 1 .009-.733l3.898-6.77a.75.75 0 0 1 .65-.376h3.132a.75.75 0 0 0 0-1.5H8.117a2.25 2.25 0 0 0-1.95 1.127l-3.897 6.77a2.25 2.25 0 0 0-.026 2.2l3.615 6.627a2.448 2.448 0 0 0 4.483-.43l4.492-14.12a.97.97 0 0 1 .923-.674");
}

</style>
