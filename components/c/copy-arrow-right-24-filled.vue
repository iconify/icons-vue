<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5orifmdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-24-filled" /></template>
<style>
.q5orifmdp {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-9 1.75a4.25 4.25 0 0 0 2.503 3.874a6.46 6.46 0 0 0 .968 3.292a3.3 3.3 0 0 1-.721.084h-5A3.25 3.25 0 0 1 3 17.75v-7.5A3.25 3.25 0 0 1 6.25 7H8.5zm9.854.896a.5.5 0 1 0-.707.707L19.293 17H14.5a.5.5 0 0 0 0 1h4.793l-1.646 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707zM17.75 3A3.25 3.25 0 0 1 21 6.25v5.774a6.502 6.502 0 0 0-9.929 4.509A3.25 3.25 0 0 1 9.5 13.75v-7.5A3.25 3.25 0 0 1 12.75 3z");
}

</style>
