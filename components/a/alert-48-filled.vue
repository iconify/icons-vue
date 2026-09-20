<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8_98uagp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-48-filled" /></template>
<style>
.f8_98uagp {
  fill: currentColor;
  d: path("M24 4C15.716 4 9 10.716 9 19v8.487l-2.804 6.355A2.25 2.25 0 0 0 8.254 37h31.492a2.25 2.25 0 0 0 2.058-3.158L39 27.487V19c0-8.284-6.716-15-15-15m0 40a6 6 0 0 1-5.917-5h11.834A6 6 0 0 1 24 44");
}

</style>
