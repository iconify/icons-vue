<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ow9paxbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-add-20-filled" /></template>
<style>
.ow9paxbma {
  fill: currentColor;
  d: path("M15.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-4.831-8c-.307.343-.54.759-.665 1.227l-3.438 12.89a.501.501 0 0 0 .967.258l3.438-12.89a2 2 0 0 1 1.81-1.48a3 3 0 0 1 2.375 1.394l3.574 5.667c.226.357.309.775.252 1.177A5.48 5.48 0 0 0 15.5 9c-1.5 0-2.858.6-3.85 1.573l1.786-6.693a.5.5 0 0 0-.966-.258L9.03 16.516a2 2 0 0 1-1.813 1.48A3 3 0 0 1 4.84 16.6l-3.574-5.667a1.75 1.75 0 0 1 0-1.868l3.941-6.25c.32-.507.88-.816 1.48-.816zM15.5 12a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H15v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 1 0 0-1H16v-1.5a.5.5 0 0 0-.5-.5");
}

</style>
