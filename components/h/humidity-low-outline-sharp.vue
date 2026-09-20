<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd_n8cbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:humidity-low-outline-sharp" /></template>
<style>
.kd_n8cbfe {
  fill: currentColor;
  d: path("M12 20.5q-2.91 0-4.955-2.006T5 13.61q0-1.373.555-2.628t1.487-2.24L12 3.884l4.958 4.858q.933.985 1.487 2.24T19 13.615q0 2.882-2.045 4.884T12 20.5m4.25-2.703Q18 16.094 18 13.615q0-1.177-.45-2.242t-1.3-1.865L12 5.3L7.75 9.508q-.85.801-1.3 1.865T6 13.615q0 2.48 1.75 4.182T12 19.5t4.25-1.703");
}

</style>
