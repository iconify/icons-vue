<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gob994zpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:business-center-outline" /></template>
<style>
.gob994zpu {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v9.769q0 .69-.463 1.153T19.385 20zM10 7h4V5.615q0-.23-.192-.423T13.385 5h-2.77q-.23 0-.423.192T10 5.615zm10 7.5h-6V16h-4v-1.5H4v3.885q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.424zm-9 .5h2v-2h-2zm-7-1.5h6V12h4v1.5h6V8.616q0-.231-.192-.424T19.385 8H4.615q-.23 0-.423.192T4 8.616zm8 .5");
}

</style>
