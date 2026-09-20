<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zxq6dn_pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-waterfall-20-filled" /></template>
<style>
.zxq6dn_pw {
  fill: currentColor;
  d: path("M1 3.5a.5.5 0 0 1 .5-.5H7a2 2 0 0 1 2 2v4.5h6c1.035 0 2 .741 2 1.8V16h1.5a.5.5 0 0 1 0 1H13c-1.035 0-2-.741-2-1.8v-4.7H5a2 2 0 0 1-2-2V4H1.5a.5.5 0 0 1-.5-.5");
}

</style>
