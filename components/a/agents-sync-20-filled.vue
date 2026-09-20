<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6q6czbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-sync-20-filled" /></template>
<style>
.z6q6czbhd {
  fill: currentColor;
  d: path("M15.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-4.831-8c-.307.343-.54.759-.665 1.227l-3.438 12.89a.501.501 0 0 0 .967.258l3.438-12.89a2 2 0 0 1 1.81-1.48a3 3 0 0 1 2.375 1.394l3.574 5.667c.226.357.309.775.252 1.177A5.48 5.48 0 0 0 15.5 9c-1.5 0-2.858.6-3.85 1.573l1.786-6.693a.5.5 0 0 0-.966-.258L9.03 16.516a2 2 0 0 1-1.813 1.48A3 3 0 0 1 4.84 16.6l-3.574-5.667a1.75 1.75 0 0 1 0-1.868l3.941-6.25c.32-.507.88-.816 1.48-.816zM13.5 15a.5.5 0 0 0-.5.5V17a.5.5 0 0 0 1 0v-.152a3 3 0 0 0 1.447.402a3 3 0 0 0 2.174-.879a.5.5 0 1 0-.707-.707a2 2 0 0 1-2.382.336H15a.5.5 0 1 0 0-1zm4-3.5a.5.5 0 0 0-.5.5v.152a3 3 0 0 0-2.624-.183a3 3 0 0 0-.997.66a.5.5 0 0 0 .707.707A2 2 0 0 1 16.468 13H16a.5.5 0 0 0 0 1h1.5a.5.5 0 0 0 .5-.5V12a.5.5 0 0 0-.5-.5");
}

</style>
