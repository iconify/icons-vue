<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4gyktypv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-2-24-regular" /></template>
<style>
.p4gyktypv {
  fill: currentColor;
  d: path("M3.75 17a.75.75 0 0 1 .743.648l.007.102v1.5a.75.75 0 0 1-1.493.102L3 19.25v-1.5a.75.75 0 0 1 .75-.75m8-6a.75.75 0 0 1 .743.648l.007.102v7.5a.75.75 0 0 1-1.493.102L11 19.25v-7.5a.75.75 0 0 1 .75-.75m4-3a.75.75 0 0 1 .743.648l.007.102v10.5a.75.75 0 0 1-1.493.102L15 19.25V8.75a.75.75 0 0 1 .75-.75m-8 6a.75.75 0 0 1 .743.648l.007.102v4.499a.75.75 0 0 1-1.493.102L7 19.249V14.75a.75.75 0 0 1 .75-.75");
}

</style>
