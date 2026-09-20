<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whza1_0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:double-arrow-rounded" /></template>
<style>
.whza1_0ug {
  fill: currentColor;
  d: path("M11.742 12L7.656 6.287q-.177-.25-.04-.519t.44-.268q.12 0 .229.056q.109.057.169.157L12.962 12l-4.508 6.287q-.061.1-.17.157t-.232.056q-.292 0-.433-.268q-.14-.268.037-.518zm5.797 0l-4.087-5.713q-.177-.25-.04-.519t.44-.268q.12 0 .229.056q.109.057.169.157L18.758 12l-4.508 6.287q-.061.1-.17.157t-.232.056q-.292 0-.433-.268q-.14-.268.037-.518z");
}

</style>
