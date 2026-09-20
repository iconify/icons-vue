<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilmqwzeda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hls-outline-sharp" /></template>
<style>
.ilmqwzeda {
  fill: currentColor;
  d: path("M3.308 14.692V9.308h.884v2h2.616v-2h.884v5.384h-.884v-2.5H4.192v2.5zm6.923 0V9.308h.885v4.5h2.73v.884zm5.577 0V13h.884v.808h2.616v-1.5h-3.5v-3h4.384V11h-.884v-.808h-2.616v1.5h3.5v3z");
}

</style>
