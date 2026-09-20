<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_4607hqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-24-regular" /></template>
<style>
.w_4607hqs {
  fill: currentColor;
  d: path("M7.642 7.116a1.3 1.3 0 0 0-.124.384H5a1.5 1.5 0 0 0-1.493 1.355L3.5 9v6a1.5 1.5 0 0 0 1.355 1.493L5 16.5h11.998a1.5 1.5 0 0 0 1.493-1.355l.007-.145V9a1.5 1.5 0 0 0-1.355-1.493l-.145-.007H15.05l.31-.611c.148-.293.172-.605.103-.889H17a3 3 0 0 1 3 3v1h1.001a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H20v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h3.207zm3.6-4.893c.19-.376.757-.24.757.18V6H14.2a.3.3 0 0 1 .268.436l-2.71 5.345c-.19.376-.756.24-.756-.18V8.004H8.801a.3.3 0 0 1-.268-.436z");
}

</style>
