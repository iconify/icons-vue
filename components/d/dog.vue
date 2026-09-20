<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3o16xb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dog" /></template>
<style>
.p3o16xb6e {
  fill: var(--svg-color--c3a634, #c3a634);
  d: path("M6.093 21v-7.875h-2.25v-2.25h2.25V3h6.184c5.398 0 8.059 3.98 7.87 9.042C19.96 17.057 17.832 21 12.277 21zM8.342 5.25v5.625h4.497v2.25H8.342v5.625h3.935c4.317 0 5.48-2.97 5.623-6.792c.142-3.81-1.499-6.708-5.623-6.708z");
}

</style>
