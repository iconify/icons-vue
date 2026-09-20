<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd2za2bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-outward-outline-sharp" /></template>
<style>
.jd2za2bqk {
  fill: currentColor;
  d: path("m16.712 16.308l-.727-.689l3.094-3.1H13V11.5h6.079l-3.075-3.08l.707-.69L21 12.02zm-9.404 0L3 12.019l4.289-4.288l.707.688L4.921 11.5H11v1.02H4.902l3.094 3.1z");
}

</style>
