<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nf6jfef3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:local-language-28-regular" /></template>
<style>
.nf6jfef3k {
  fill: currentColor;
  d: path("M12.75 2a.75.75 0 0 0 0 1.5h5.75v2.805c0 1.75-1.75 3.195-3.75 3.195a.75.75 0 0 0 0 1.5C17.314 11 20 9.126 20 6.305V2.75a.75.75 0 0 0-.75-.75zm-2.057 5.463a.75.75 0 0 0-1.386 0l-7.25 17.5a.75.75 0 0 0 1.386.574l2.087-5.039h8.942l2.089 5.04a.75.75 0 0 0 1.386-.575l-2.204-5.316a.75.75 0 0 0-.146-.353zm3.158 11.535h-7.7l3.85-9.289zM22.25 2a.75.75 0 0 1 .75.75V8.5h2.249a.75.75 0 1 1 0 1.5h-2.248v9.25a.75.75 0 0 1-1.5 0V9.3a1 1 0 0 1 0-.1V2.75a.75.75 0 0 1 .75-.75");
}

</style>
