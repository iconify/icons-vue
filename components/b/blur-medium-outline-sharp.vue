<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljx0qbbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blur-medium-outline-sharp" /></template>
<style>
.ljx0qbbwm {
  fill: currentColor;
  d: path("M15.192 16.5H7.5v-1h4.942q-.734-.54-1.187-1.312q-.453-.773-.54-1.688H4.963v-1h5.754q.105-.915.549-1.687T12.442 8.5H4.5v-1h10.692q1.868 0 3.184 1.316q1.316 1.315 1.316 3.181t-1.316 3.185t-3.184 1.318m2.481-2.021q1.02-1.022 1.02-2.481T17.67 9.519T15.19 8.5t-2.478 1.022t-1.02 2.48t1.022 2.479t2.48 1.019t2.479-1.022M4.308 16.5v-1H5.73v1z");
}

</style>
