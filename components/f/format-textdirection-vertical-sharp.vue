<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8klvzbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-textdirection-vertical-sharp" /></template>
<style>
.a8klvzbba {
  fill: currentColor;
  d: path("M6.77 17.308v-3.75q-1.574 0-2.672-1.099T3 9.79t1.098-2.672T6.769 6.02h6.577v1h-2v10.289h-1V7.019H7.77v10.289zM17.557 19l-3.442-3.308l.707-.707l2.235 2.113V6.019h1v11.079l2.234-2.12l.708.714z");
}

</style>
