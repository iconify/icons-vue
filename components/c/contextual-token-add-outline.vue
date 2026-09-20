<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cas6fll0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contextual-token-add-outline" /></template>
<style>
.cas6fll0x {
  fill: currentColor;
  d: path("M19.385 19H4.615q-.69 0-1.152-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h9.039v1H4.616q-.231 0-.424.192T4 6.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-6.231h1v6.23q0 .691-.462 1.154T19.385 19M6.769 15.346H12.5v-1.961H6.77zm0-4.73H12.5V8.654H6.77zm8.5 4.73h1.962v-4.192h-1.962zM4 18V6zm14-9V7h-2V6h2V4h1v2h2v1h-2v2z");
}

</style>
