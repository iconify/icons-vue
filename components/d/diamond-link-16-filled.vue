<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4-qhbydg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-16-filled" /></template>
<style>
.s4-qhbydg {
  fill: currentColor;
  d: path("M7.383 4.36a5.536 5.536 0 0 1 2.959 9.121l-.196.206l-.728.728a2 2 0 0 1-2.829.001l-4.999-5a2 2 0 0 1 0-2.829l.728-.728a5.6 5.6 0 0 1 1.028-.81a6.6 6.6 0 0 0-.06 1.963l-.635.636a.5.5 0 0 0 0 .707l4.999 5a.5.5 0 0 0 .707 0l.728-.729l.144-.151a4.035 4.035 0 0 0-2.453-6.7c.076-.505.276-.994.607-1.415M6.59 1.586a2 2 0 0 1 2.83 0l4.998 4.998c.78.781.78 2.048 0 2.83l-.731.73a5.6 5.6 0 0 1-1.03.81a6.6 6.6 0 0 0 .06-1.963l.64-.638a.5.5 0 0 0 0-.707l-4.998-5a.5.5 0 0 0-.708 0l-.731.731a4.035 4.035 0 0 0 2.308 6.85a3 3 0 0 1-.608 1.416a5.535 5.535 0 0 1-2.76-9.325l-.001-.001z");
}

</style>
