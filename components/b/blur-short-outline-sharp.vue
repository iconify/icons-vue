<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytwd96mka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blur-short-outline-sharp" /></template>
<style>
.ytwd96mka {
  fill: currentColor;
  d: path("M17.673 14.479q1.02-1.022 1.02-2.481T17.67 9.519T15.19 8.5t-2.478 1.022t-1.02 2.48t1.022 2.479t2.48 1.019t2.479-1.022m-2.48 2.022q-1.743 0-3.022-1.134q-1.279-1.135-1.455-2.866H6.462v-1h4.254q.086-.915.539-1.687q.453-.773 1.187-1.313H4.5v-1h10.692q1.868 0 3.184 1.316q1.316 1.315 1.316 3.181t-1.316 3.185t-3.184 1.318");
}

</style>
