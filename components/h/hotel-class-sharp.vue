<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxbkq2b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hotel-class-sharp" /></template>
<style>
.cxbkq2b5i {
  fill: currentColor;
  d: path("m15.508 14.116l3.473-3l1.442.134l-3.746 3.229l1.108 4.887l-1.224-.743zM13.6 8.219l-.973-2.296l.554-1.365l1.588 3.77zM5.825 18.923l1.24-5.313l-4.123-3.572l5.431-.47l2.127-5.01l2.127 5.01l5.43.47l-4.123 3.572l1.241 5.313l-4.675-2.821z");
}

</style>
