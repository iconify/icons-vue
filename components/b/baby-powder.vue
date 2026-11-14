<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c49zfqbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-powder" /></template>
<style>
.c49zfqbxh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 8.75q-.907 0-1.431-.684q-.457-.596-.378-1.391q.164-1.638 1.72-1.882q.586-1.768 2.458-2.268q1.614-.43 2.631.37q1.017-.8 2.631-.37q1.872.5 2.458 2.268q1.556.244 1.72 1.882q.079.795-.378 1.391q-.524.684-1.431.684zM9.875 10h4.25q2.123 0 3.624 1.501q1 1.001 1.334 2.277q.081.1.124.222q.043.121.043.25q0 .118-.036.23q.036.315.036.645v2q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T4.75 17.125v-2q0-.33.036-.645q-.036-.112-.036-.23q0-.129.043-.25q.043-.122.124-.222q.334-1.276 1.334-2.277Q7.752 10 9.875 10");
}

</style>
