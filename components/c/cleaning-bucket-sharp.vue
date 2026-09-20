<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tif1otynn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cleaning-bucket-sharp" /></template>
<style>
.tif1otynn {
  fill: currentColor;
  d: path("M7.885 22L6.154 9h11.712l-1.731 13zm5.884-7.23q.731-.728.731-1.77v-1.5h-1V13q0 .617-.441 1.059q-.442.441-1.059.441t-1.059-.441T10.5 13v-1.5h-1V13q0 1.042.729 1.77q.728.73 1.769.73t1.771-.73m1.233-7.79q-.415 0-.709-.29T14 5.983t.291-.709t.707-.293t.709.29t.293.708t-.291.709t-.707.293M10 5.98q-.82 0-1.41-.59T8 3.97t.59-1.41t1.42-.58t1.41.58t.58 1.42q0 .819-.58 1.41q-.58.59-1.42.59");
}

</style>
