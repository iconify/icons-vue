<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r4rkvpbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-databricks" /></template>
<style>
.r4rkvpbwh {
  fill: var(--svg-color--ff3621, #ff3621);
  d: path("M3.082 9.3v.844l12.921 7.288l11.539-6.518v2.635l-11.539 6.557l-12.27-6.972l-.651.362v5.043l12.921 7.272l11.539-6.494v2.612l-11.539 6.559l-12.27-6.973l-.651.362v.855l12.921 7.271l12.919-7.27v-5.048l-.659-.359l-12.26 6.971l-11.542-6.558V15.14l11.542 6.486l12.921-7.27V9.379l-.659-.361l-12.262 6.975L5.054 9.769l10.949-6.184l9.019 5.096l.789-.443v-.696l-9.808-5.538Z");
}

</style>
