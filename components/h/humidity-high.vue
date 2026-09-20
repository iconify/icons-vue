<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8umcgblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:humidity-high" /></template>
<style>
.o8umcgblu {
  fill: currentColor;
  d: path("M12 20.5q-2.91 0-4.955-2.006T5 13.61q0-1.373.555-2.628t1.487-2.24L10.87 4.99q.242-.22.534-.34q.291-.12.593-.12t.597.12t.538.34l3.827 3.752q.933.985 1.487 2.24T19 13.615q0 2.882-2.045 4.884T12 20.5");
}

</style>
