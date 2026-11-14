<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rskb41bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gift-box-shipping" /></template>
<style>
.rskb41bor {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7.736q-.359.014-.75.014t-.75-.014V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6.625q-3.375 0-3.375-3.375v-4.75q0-.92.251-1.589Q2.25 10.518 2.25 8.75q0-2.5 2.5-2.5h2.542q-.479-1.222-.019-2.016q.519-.896 1.708-.726q1.651.235 3.019 2.108q1.368-1.873 3.019-2.108q1.189-.17 1.708.726q.46.794-.019 2.016h2.542q1.036 0 1.768.732t.732 1.768t-.732 1.768q-.259.258-.555.426q.287.697.287 1.681v4.75q0 3.375-3.375 3.375H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146z");
}

</style>
