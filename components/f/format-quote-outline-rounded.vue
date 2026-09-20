<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9pfmbbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-quote-outline-rounded" /></template>
<style>
.s9pfmbbhw {
  fill: currentColor;
  d: path("m7.012 16.558l1.969-3.424q-.173.097-.404.135t-.461.039q-1.4 0-2.354-.972q-.954-.971-.954-2.336q0-1.4.954-2.354t2.354-.954q1.364 0 2.336.954t.971 2.347q0 .486-.118.906t-.336.793l-3.098 5.366q-.062.112-.175.181t-.25.069q-.288 0-.431-.25t-.003-.5m8.769 0l1.969-3.423q-.173.096-.404.134t-.461.039q-1.4 0-2.354-.972q-.954-.971-.954-2.336q0-1.42.954-2.363t2.354-.945q1.364 0 2.336.954t.971 2.347q0 .486-.118.906t-.335.793l-3.099 5.366q-.062.112-.175.181t-.25.069q-.288 0-.431-.25t-.003-.5m-6.113-5.005q.64-.64.64-1.553t-.64-1.553t-1.552-.64q-.914 0-1.553.64q-.64.64-.64 1.553t.64 1.553t1.553.64t1.552-.64m8.77 0q.639-.64.639-1.553t-.64-1.553t-1.553-.64t-1.552.64q-.64.64-.64 1.553t.64 1.553t1.552.64q.914 0 1.553-.64M8.117 10");
}

</style>
