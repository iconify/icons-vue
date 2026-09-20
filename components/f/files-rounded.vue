<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woqtu8brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:files-rounded" /></template>
<style>
.woqtu8brf {
  fill: currentColor;
  d: path("M4.616 19q-.667 0-1.141-.475T3 17.386V14.23h7.616q.666 0 1.14-.475t.475-1.14V5h7.154q.666 0 1.14.475T21 6.615v10.77q0 .666-.475 1.14t-1.14.475zM3 13.942V8.616q0-.667.475-1.141T4.615 7h5.327zm2.114-.711l6.117-6.117v5.502q0 .269-.173.442t-.442.173z");
}

</style>
