<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifwz5jrhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-external-input-outline-sharp" /></template>
<style>
.ifwz5jrhy {
  fill: currentColor;
  d: path("M4 17V7zm-2 2V5h20v8.525q-.425-.4-.925-.687T20 12.35V7H4v10h8.1q-.05.25-.062.488t-.013.512t.013.513t.062.487zm6-5v2h4.35q.2-.575.5-1.075t.7-.925zm-3-3v2h2v-2zm3 0v2h2v-2zm3 0v2h2v-2zm3 0v2h.7q.3-.2.625-.363T16 12.35V11zm3 0v1.1q.25-.05.488-.075T18 12t.513.025t.487.075V11zM5 8v2h2V8zm3 0v2h2V8zm3 0v2h2V8zm3 0v2h2V8zm3 0v2h2V8zm1 14l-1.4-1.4l1.575-1.6H14v-2h4.175L16.6 15.4L18 14l4 4z");
}

</style>
